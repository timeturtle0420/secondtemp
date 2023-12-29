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

### 교수님 블로그 참조
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

 