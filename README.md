# secondtemp

## 두번째 시도 

### 업데이트 기록

*readme 파일 수정 정상작동*

* git add . git commit -m . git push 정상작동 

pip install git+https://github.com/quarto-dev/quarto-cli 정상작동 #quarto 설치(?) -일단 작동

_quarto.yml , energy.qmd 생성 및 작성 완료

quarto render energey.qmd  입력 - 정상작동...하는 듯? > 페이지 정상적으로 만들어진것 같음 

https://timeturtle0420.github.io/secondtemp/energey.html

* ##Column {width=50%} \to\ Row {height=60%} 로 바꿨는데 작동안함...

site의 내용 및 layout 변경을 위해선 energey.qmd 파일의 파이썬 코드를 변경후 
* quarto render 
* git push 
절차를 거치면 되는듯...?

### 교수님 블로그 참조(_quarto.yml 변경)
- _quarto.yml 파일 변경

기존
``` 
project:
  type: website
  output-dir: docs

```

이후
```
project:
  type: website
  output-dir: docs

website:
  title: "About me"
  navbar:
    right:
      - icon: github
        href: https://github.com/timeturtle0420
      - icon: youtube
        href: https://www.youtube.com/@user-lx8ks6er1s
format:
  html:
    theme: cosmo
    css: styles.css
```
- 결과 

제대로 바뀜 git render 이후 git add . , git commit -m . , git push 해야하는듯?

- 교수님의 블로그 방식: 1.하나의 강의에 대한 개별 수업들의 블로그 2. 개별 수업들을 합쳐 한 강의에 대한 블로그 작성 3. 그러한 강의들이 모인 블로그를 작성

- _quarto.yml 의 변경은 웹사이트의 기본 형태?에 대한 변경을 이끌어내는 것 같음
- 내용에 대한 변경은 .qmd 를 통해서 이루어지는 것 같다....

- **Next** 블로그 안에 파일을 넣는 방법-posts파일에 집어 넣는건가?






# 수업
cli를 이용. 우리가 마우스를 이용해 그래픽이 나오면 사용하는 방법은 gui이나, gui는 그냥 cli와 같음(대응하는 cli가 있는 것 뿐)

