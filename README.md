# RateLimit
PHP Rate Limiting Library With Token Bucket Algorithm.

CREATE TABLE `rate-limiter`.`ratelimit` ( `id` INT UNSIGNED NOT NULL AUTO_INCREMENT , `key` INT NOT NULL , `data` INT NOT NULL , `deadline` INT NOT NULL , PRIMARY KEY (`id`)) ENGINE = InnoDB;