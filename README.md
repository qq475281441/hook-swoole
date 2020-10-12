# hook-swoole
有些swoole扩展会直接调用swoole_version函数，如果你的项目在php-fpm中运行的话，会报函数不存在


`比如saber扩展`