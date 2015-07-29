# mecab-ko

본 Docker 이미지는 은전한닢 프로젝트(http://eunjeon.blogspot.kr/)의 mecab-ko와 mecab-ko-dic을 이용한 것입니다.

- https://bitbucket.org/eunjeon/mecab-ko
- https://bitbucket.org/eunjeon/mecab-ko-dic

# Usage
```
$ sudo docker pull koorukuroo/mecab-ko
$ sudo docker run -i -t koorukuroo/mecab-ko:0.1
안녕하세요
안녕	NNG,*,T,안녕,*,*,*,*
하	XSV,*,F,하,*,*,*,*
세요	EP+EF,*,F,세요,Inflect,EP,EF,시/EP/*+어요/EF/*
EOS
```

# Docker
- https://registry.hub.docker.com/u/koorukuroo/mecab-ko/
