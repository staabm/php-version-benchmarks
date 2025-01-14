### AWS ARM64 (c6g.4xlarge)

|  Attribute  |     Value   |
|-------------|-------------|
|Environment|aws|
|Runner|host|
|Instance type|c6g.4xlarge|
|Architecture|aarch64
|CPU|16 cores|
|RAM|30 GB|
|Kernel|4.14.243-185.433.amzn2.aarch64|
|OS|Amazon Linux 2|
|Time|2021-10-01 22:01:00|

### Laravel demo app - 25 consecutive runs, 250 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP 7.4](https://github.com/php/php-src/commit/4d442714155a305205cdd3785ab024f3eba7516f)|1.42321|1.46909|0.01047|1.44002|0.00%|1.43880|0.00%|33.23 MB|
|[PHP 8.0](https://github.com/php/php-src/commit/5db6e358436f9e8cda82b3154558e22d53eba963)|1.33763|1.38337|0.01167|1.35488|-6.28%|1.35153|-6.46%|32.88 MB|
|[PHP 8.1](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|1.09937|1.11531|0.00426|1.10633|-30.16%|1.10474|-30.24%|35.69 MB|
|[PHP 8.1 (JIT)](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|1.08847|1.10770|0.00528|1.09726|-31.24%|1.09472|-31.43%|44.26 MB|
|[PHP 8.1 (preloading)](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|1.09952|1.14373|0.01074|1.11166|-29.54%|1.10794|-29.86%|35.55 MB|

### Symfony demo app - 25 consecutive runs, 250 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP 7.4](https://github.com/php/php-src/commit/4d442714155a305205cdd3785ab024f3eba7516f)|1.69716|1.78182|0.02411|1.73042|0.00%|1.72586|0.00%|32.97 MB|
|[PHP 8.0](https://github.com/php/php-src/commit/5db6e358436f9e8cda82b3154558e22d53eba963)|1.64042|1.71455|0.01864|1.67314|-3.42%|1.67055|-3.31%|32.60 MB|
|[PHP 8.1](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|1.27810|1.30092|0.00615|1.28944|-34.20%|1.28833|-33.96%|33.17 MB|
|[PHP 8.1 (JIT)](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|1.25499|1.30118|0.01221|1.26983|-36.27%|1.26876|-36.03%|42.26 MB|
|[PHP 8.1 (preloading)](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|1.27979|1.32661|0.01014|1.29287|-33.84%|1.29119|-33.66%|33.44 MB|

### bench.php - 15 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP 7.4](https://github.com/php/php-src/commit/4d442714155a305205cdd3785ab024f3eba7516f)|0.34446|0.34869|0.00174|0.34673|0.00%|0.34738|0.00%|22.94 MB|
|[PHP 8.0](https://github.com/php/php-src/commit/5db6e358436f9e8cda82b3154558e22d53eba963)|0.33641|0.34044|0.00129|0.33828|-2.50%|0.33786|-2.82%|22.75 MB|
|[PHP 8.1](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|0.34798|0.35785|0.00269|0.35029|1.02%|0.34974|0.67%|23.19 MB|
|[PHP 8.1 (JIT)](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|0.10972|0.11179|0.00056|0.11015|-214.79%|0.10989|-216.12%|24.78 MB|
|[PHP 8.1 (preloading)](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|0.34653|0.35469|0.00240|0.34950|0.79%|0.34824|0.25%|23.14 MB|

### micro_bench.php - 15 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP 7.4](https://github.com/php/php-src/commit/4d442714155a305205cdd3785ab024f3eba7516f)|2.23846|2.24565|0.00166|2.24170|0.00%|2.24179|0.00%|16.86 MB|
|[PHP 8.0](https://github.com/php/php-src/commit/5db6e358436f9e8cda82b3154558e22d53eba963)|2.10135|2.11038|0.00219|2.10511|-6.49%|2.10475|-6.51%|16.85 MB|
|[PHP 8.1](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|2.06715|2.07220|0.00125|2.06913|-8.34%|2.06879|-8.36%|17.20 MB|
|[PHP 8.1 (JIT)](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|1.20088|1.20699|0.00194|1.20278|-86.38%|1.20229|-86.46%|18.45 MB|
|[PHP 8.1 (preloading)](https://github.com/php/php-src/commit/52e7e0f521f6002bb84a20e4be5269617afa071d)|2.04956|2.05577|0.00182|2.05308|-9.19%|2.05336|-9.18%|17.18 MB|
