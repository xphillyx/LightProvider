# 개발중


# LightProvider - Python-based LightComics Server
파이선3 베이스로 작성된 LightComics 압축파일 스트리밍 서버입니다.

현재 테스트플라이트 버전에 기능이 포함되어 있습니다.




## 필요 패키지
```
Flask
Pillow
```

## 지원
현재 zip 파일만 지원합니다.


## How To Run?
설정파일
```
{
  "ROOT": "/home/user/ec2-user/manhwa",
  "PORT": 8909,
  "HOST": "0.0.0.0",
  "PASSWORD": "TEST"
}
```

```
python lightcomics.py &
```


## TODO
- [O] Support Linux base OS 
- [-] Support Windows OS
- [-] Support Mac OSX
