# hello-world-actix-web

**通过`actix-web`框架构建的`Rust` Web项目**

```shell
$ wrk -t 8 -c 8 -d 10s 'http://127.0.0.1:8080' —-latency

Running 10s test @ http://127.0.0.1:8080
  8 threads and 8 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency    97.45us   64.75us   4.56ms   99.38%
    Req/Sec    10.39k   538.85    11.08k    91.34%
  835630 requests in 10.10s, 70.13MB read
Requests/sec:  82739.89
Transfer/sec:      6.94MB
```

![actix-web](https://raw.githubusercontent.com/why168/hello-world-actix-web/master/art/2023-08-07_17.29.12.png)
