# deokgu.github.io

### Locally

Before you start make sure you have *Ruby* and the gems for *Jekyll* installed locally. You can find out how to do that [here](https://jekyllrb.com/docs/installation/).

*Note: You will need version `1.15.2` of bundler, as this is the only version that Heroku supports.*

1. Fork and or clone this repository locally
2. `cd modern-resume-theme`
3. `bundle install`
4. `bundle exec jekyll serve`
5. Open your browser to `http://localhost:4000`

Any changes you make will automatically build and you will be able to see these by refreshing your browser. To find out more about *Jekyll* take a look [here](https://jekyllrb.com/docs/usage/).

***Note:** You will need to re-run `bundle exec jekyll serve` to see changes made in `_config.yml`.*


### whktmltopdf

#### html to pdf 
1. wkhtmltopdf 파일 설치 
2. C:\Program Files\wkhtmltopdf\bin으로 이동 후 shift + 마우스 오른쪽 -> 여기에 Powershell 창열기
3. .\wkhtmltopdf "{html 사이트 & localhost:4000}" "{저장 local 경로}"

4. my pc
```
cd C:\Program Files\wkhtmltopdf\bin
.\wkhtmltopdf "localhost:4000" "C:\Users\onefe\git\deokgu94.github.io\곽민구_github_cv.pdf"
```