# Research
## Question 1:

-   Symfony kullanarak aynı kod için harcayacağımız süreyi sağladığı kolaylıklar ile kısaltırız.
-   Hazır kütüphaneleri, modülleri tek satır kod ile projemize çağırabiliriz.
-   CSRF, XSS, SQL Injection vs. gibi birçok saldırıya karşı koruma sağlar.
-   Console komutlarını tek bir kodda otomatikleştirebiliriz.
-   Doctrine ORM ve Twig motoru hazır olarak bulunur.
-   Developer Toolbar sayesinde her işlemin performansını ölçebilirsiniz.
## Question 2:
Örnek verecek olursak : 
```
imports:
    - { resource: config.yml }
    - { resource: parameters_dev.yml }
```

## Question 3:
Composer ile web uygulaması oluşturma : 
```
composer create-project symfony/skeleton:"^5.4" my_project_directory
$ cd my_project_directory
$ composer require webapp
```
Alternatif komut ile web uygulaması oluşturma :
```
symfony new my_project_directory --version=5.4 --webapp
```
## Question 4:
-  Laravel, veri tabanı erişimi için Eloquent; Symphony ise Doktrin işleme modülünü kullanır.
-  Laravel Blade şablonlama sistemini kullanırken Symphony Twig sistemini kullanır.
