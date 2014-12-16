Slug

Generate Slug from Cyrillic

Установка
================
Установка через composer.

Откройте файл `composer.json`  вашего проекта и впишите:

	"require": {
		"flydes/slug": "dev-master"
	},

Далее в терминале обновите composer командой
    `composer update`

Далее откройте файл `config/app.php`,  добавьте.

  `'Flydes\Slug\SlugServiceProvider',`

Также добавьте alias

`'Slug' => 'Flydes\Slug\Facades\Slug',`

    
  
Вызов метода
====================
`Slug::make($text)` 
