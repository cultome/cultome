```console
               ___    __
              /\_ \  /\ \__
  ___   __  __\//\ \ \ \ ,_\   ___     ___ ___      __
 /'___\/\ \/\ \ \ \ \ \ \ \/  / __`\ /' __` __`\  /'__`\
/\ \__/\ \ \_\ \ \_\ \_\ \ \_/\ \L\ \/\ \/\ \/\ \/\  __/
\ \____\\ \____/ /\____\\ \__\ \____/\ \_\ \_\ \_\ \____\
 \/____/ \/___/  \/____/ \/__/\/___/  \/_/\/_/\/_/\/____/
 
$ tree .
.
├── bio.txt
├── techs
│   ├── aws
│   ├── dbs
│   │   ├── elasticsearch.backup
│   │   ├── neo4j.shp
│   │   ├── pg.bin
│   │   └── redis.mem
│   └── langs
│       ├── crystal.jpeg
│       ├── golang.png
│       ├── java.gif
│       ├── javascript.jpg
│       ├── nim.jpg
│       ├── python.png
│       └── ruby.png
└── TODO.md

$ hexdump techs/aws
0000000 apig gate way0 apps ync0 0s30 0ec2 0cod
0000010 e0bu ild0 ecac he00 open sear ch00 0rds
0000020 lamb da00 xray 0ecs 3388 clou dfro nt00
0000030 0000 0000 0040 0038 000d 0040 001c 001b

$ cat bio.txt
Carlos Soria...
Mexican programmer...
Likes to program...
Dislikes to write bios.

$ glow TODO.md

   TODO

  [✓] Update my GH profile
  [ ] Learn Prolog, Racket and Lisp before I die
  [ ] Finish HL Alyx
  [ ] Finish previous years of AoC
  [ ] Defragment my HDD
  [ ] Find a way to live near the beach (maybe)
  
$ exit
```
