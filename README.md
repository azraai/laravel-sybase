# sybase-eloquent
Eloquent module to run Sybase with minimal problems using Laravel 5.x.
- Enables use of multiple kinds of fields.
- Use default eloquent: works with odbc and dblib!

### Install
- Require in your **composer.json** this package: ``"mainginski/sybase-eloquent": "dev-master"``
- Run ``composer update``
- Add to your providers in **./config./app.php**:
``Mainginski\SybaseEloquent\Database\SybaseServiceProvider::class``