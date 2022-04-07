# Junior android developer (kotlin). 

## Стек технологий 
<details> 
   
   + Kotlin
   
   + Android SDK
   
   + Retrofit
   
   + jetpack libs
   
   + Jetpack Compose (использовал, сейчас изучение отложено)
   
   + ViewBinding
   
   + Kotlin Coroutines
   
   + MVVM
   
   + ClearArchitecture
   
   + DI (Hilt)
   
   + ROOM.
  
</details>

## Курсы

<details>[Developing Android Apps with Kotlin](https://classroom.udacity.com/courses/ud9012)
</details>

Проекты:
<details>

   + [Текущий проект](https://github.com/zdezak/Coder)

   + [Тестовое задание по работе с LastFM (Compose)](https://github.com/zdezak/getInfoAboutAlbums). [(Fragment)](https://github.com/zdezak/getArtist). (23.12.2021)        <details>

       +Описание: Приложэение получает данные с API и выводит на экран. По кнопке отправляется новый запрос.

       +Используемые технологии:

           - Retrofit для отправки запросов,

           - Moshi для конвертирования ответа в data class,

           - В Fragment для отображения RecyclerView. Список и Сетка для изображений,

           - В Compose для отображения LazyList и LazyList для изображений.

   </details>


   + [getmeaxolotl](https://github.com/zdezak/getmeaxolotl). (24.08.2021)
   <details>

       +Описание: Приложэение получает данные с API и выводит на экран. По кнопке отправляется новый запрос.

       +Используемые технологии:

           - Retrofit для отправки запросов,

           - Moshi для конвертирования ответа в data class,

           - Activity и ViewModel, без фрагментов.

   </details>


   + [Notes](https://github.com/zdezak/Notes). (08.08.2021)
   <details>

     + Описание: Простое приложение для заметок. Отображение, добавление, редактирование, удаление.Построено на взаимодействии фрагментов. Одно activity.

     + Искользуемые технологии:

       - DataBinding для создания объектов каждого layout.xml. Нет постоянного поиска по id,

       - Room для сохранения данных,

       - RecyclerView для отображения,

       - Safe-arg для передачи данных между фрагментами,

       - Androidx.navigation для перемещения между фрагментами,

       - ViewModel для разделения фрагмента от данных,

       - ViewModelfactory для передачи параметров ViewModel при создании,

       - Coroutines для взаимодействия с базой данных в viewModel через viewModelScope,

       - LiveData для данных и для наблюдения перед сохранением и переходами. В layout.xml добавлены функции для изменения переменной liveData и выполенния действий. 

   </details>
   
</details>
