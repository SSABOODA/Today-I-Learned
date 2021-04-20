# pip

pip는 'pip installs package'의 약자로 '파이썬 패키지 관리 시스템'이다. 파이썬 패키지, 모듈을 설치하고 관리하는데 사용한다.

## 1. pip 설치여부 확인

### (1) 파이썬3 및 파이썬2.7.9이상

파이썬을 사용중이면 **pip3**이 기본으로 설치되어 있다.

- pip3 설치여부 확인

```
$ pip3
```

- pip3 버전 확인 및 업그레이드

```
$ pip3 -V
$ pip3 install --upgrade pip
```

### (2) 파이썬 2.7.9 하위버전

- pip 설치여부 확인

```
$ pip
```

## 2. homebrew 설치

pip3도 pip도 없으면 설치한다.
먼저 `homebrew`를 설치한다. `homebrew`란 맥OS용 패키지 관리 프로그램을 말한다. 맥에서 프로그램 설치를 도와주는 프로그램이다.

- homebrew 버전확인

```
$ brew -v
```

- 없을 경우 homebrew 설치

```
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

삭제는 install 대신 uninstall을 적으면 된다.

- homebrew 업데이트

```
$ brew update
```

- pip 설치

```
$ sudo easy_install pip
```

\*참고: sudo: `super user do`
