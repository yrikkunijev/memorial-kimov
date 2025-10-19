# Мемориальный сайт Кимова Тембота Эльмурзовича — с фотоархивом

## Фотогалерея по годам
На странице `gallery.html` можно фильтровать фотографии по годам и просматривать их во всплывающем окне.

### Как добавить фотографии
1. Поместите изображения в папку `assets/` (например, `assets/1941_photo1.jpg`).
2. В `gallery.html` добавьте строку:
   ```html
   <img src="assets/1941_photo1.jpg" alt="Описание" class="photo 1941">
   ```
3. Чтобы добавить новый год, добавьте кнопку в фильтр:
   ```html
   <button class="filter-btn" data-year="1980">1980</button>
   ```

## Публикация на GitHub Pages
1. Загрузите файлы в репозиторий `memorial-kimov`.
2. Включите GitHub Pages (Settings → Pages → Branch: `main`, Folder: `/`).
3. Сайт появится по адресу: https://yrikkunijev.github.io/memorial-kimov/
