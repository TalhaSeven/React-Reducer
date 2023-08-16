# React UseReducer Example

This project demonstrates the use of the `useReducer` hook in a React application. It showcases a simple functionality of fetching cat images from an API and displaying them based on different states using a reducer.

## Components

### App Component

The `App` component serves as the entry point of the application. It imports and renders the `UseReducerExample` component.

### initialState and reducer

The `initialState` object defines the initial state of the component. It includes properties for `loading`, `catImage`, and `error`.

The `reducer` function takes the current state and an action as parameters and returns a new state based on the action type.

### UseReducerExample Component

The `UseReducerExample` component demonstrates the use of `useReducer` hook along with the `initialState` and `reducer`. This component fetches a cat image from an API and handles different states such as loading, success, and failure.

- The `getCatImage` function sends a fetch request to the cat image API. It dispatches actions to the reducer to handle loading, success, and failure states.

- The component renders a "Get Cat Image" button that triggers the `getCatImage` function. The button is disabled during loading.

- If an error occurs during the fetch, it displays an error message. If the fetch is successful, it displays the fetched cat image.


# React UseReducer Örneği

Bu proje, bir React uygulamasında `useReducer` kancasının kullanımını göstermektedir. Bir azaltıcı (reducer) kullanarak farklı durumlar temelinde API'den kedi resimleri çekme işlevselliğini basitçe sergiler.

## Bileşenler

### App Bileşeni

`App` bileşeni, uygulamanın giriş noktası olarak hizmet eder. `UseReducerExample` bileşenini içe aktarır ve bu bileşeni render eder.

### initialState ve reducer

`initialState` nesnesi bileşenin başlangıç durumunu tanımlar. Bu durum, `loading`, `catImage` ve `error` özelliklerini içerir.

`reducer` fonksiyonu mevcut durumu ve bir eylemi parametre olarak alır ve eylem türüne dayalı olarak yeni bir durum döndürür.

### UseReducerExample Bileşeni

`UseReducerExample` bileşeni, `useReducer` kancasının ve `initialState` ile `reducer`'ın kullanımını sergiler. Bu bileşen, bir kedi resmini bir API'den almayı ve yükleme, başarı ve hata gibi farklı durumları ele almayı gösterir.

- `getCatImage` fonksiyonu, kedi resmi API'ye bir talep gönderir. Yükleme, başarı ve hata durumlarıyla başa çıkmak için azaltıcıya eylemler gönderir.

- Bileşen, "Kedi Resmi Al" adlı bir düğme render eder. Bu düğme, yükleme sırasında devre dışı bırakılır.

- İstekte bir hata oluşursa, hata mesajını görüntüler. İstek başarılı ise, alınan kedi resmini görüntüler.

