# [ํ๋ธ๋ก **<Gelato map in Rome๐ฆ>**]([https://public.tableau.com/views/_16594472938490/1?:language=ko-KR&:display_count=n&:origin=viz_share_link)
## ๊ฒฐ๊ณผ๋ฌผ 
<img width="820" alt="image" src="https://user-images.githubusercontent.com/88447983/188470181-15ad6413-58d9-40a8-87ec-31407f4644ce.png">)
## ํฌ๋กค๋ง
- ์๋ ๋์, ํฌ๋กฌ ์น ๋๋ผ์ด๋ฒ๋ก ๊ตฌ๊ธ๋งต ํฌ๋กค๋ง ์๋ -> ์คํจ (๊ฐ๊ฒ๋ณ๋ก csv๊ฐ ์ ์ฅ๋๋ ํํ๋ ๊ฐ๋ฅํ๋, dataframe์ผ๋ก ๋ง๋ค์ด์ผํจ.)
- Instant Data Scraper : ํฌ๋กฌ ํ์ฅํด (๊ตฌ๊ธ๋งต ๊ฐ๊ฒ ์ด๋ฆ, ์ฃผ์, rating, ์น์ฌ์ดํธ, ๋ฆฌ๋ทฐ ๊ฐ์ ๋ฑ ํฌ๋กค๋ง ๊ฐ๋ฅ)
- xlsx ํํ๋ก ์ ์ฅ
## ์ ์ฒ๋ฆฌ
- ์ ๋ขฐ๋ ์๋ ์ง๋๋ฅผ ๋ง๋ค๊ธฐ ์ํด ๋ฆฌ๋ทฐ ์๊ฐ 1000๊ฐ ์ด์์ธ ๊ฐ๊ฒ๋ง ์์ง : tableau ๋ด๋ถ ํด์ ์ด์ฉํ์ฌ ์กฐ๊ฑด ์ถ๊ฐ
- latitude ์ longitude๊ฐ null์ธ ๊ฐ๊ฒ๋ฅผ ์ ์ธ
## mapping
- longitude์ latitude๋ฅผ ์ฐจ๋ก๋๋ก ํด๋ฆญํ๊ณ , name์ ์ธ๋ถ์ ๋ณด์ ๋๋ฉด mapping ์๋ฃ
- rating ์์, ํฌ๊ธฐ, ๋ ์ด๋ธ์ ๋๊ธฐ
- ๋งต์ ์๋จ ํด์์ '๊ฑฐ๋ฆฌ'๋ก 
## rank
- rank ์ฝ๋๋ฅผ ์๋ ฅํ๊ณ  sum์ ํด์ฃผ์ด์ผ ํ๋ฉฐ, ๋ถ์ฐ์์ฑ์ผ๋ก ๊ผญ ๋ฐ๊ฟ์ฃผ์ด์ผํจ
- ๊ทธ ์ธ๋ก๋ ์ค์๋ก ๋ฐ๊พธ๊ธฐ ๋ฑ๋ฑ
## dashboard
- ๊ฐ๋ก๋ก ์ค์ ํ ๋ค
- ๊ฐ ์๋ฆฌ์ ์ํธ ๋ฐฐ์นํ๊ณ 
- ์ด๋ฏธ์ง๋ url ๋ฃ์ด์ฃผ๊ธฐ
## ๊ฐ์ ์ 
- ๊ด๊ด์ง๋ ์ญ์ผ๋ก๋ถํฐ ๊ฑฐ๋ฆฌ์ ์๋ฅผ ๋ถ์ฌํ์ฌ Ranking ์ด๋ mapping ํ๊ธฐ
- ์์ง Italy์ postal code๋ ํ๋ธ๋ก ๋งต์ ๋ฑ๋ก์ด ๋์ง ์์์์ด์ ๊ฒฝ๋,์๋๋ฅผ ์ง์  ์๋ ฅํด์ผํ๋ค.
- ํ๋ธ๋ก ๋ฐ์คํฌํ ์ฌ์ผํ๋.. ์์ธ๋ก ์ ์ฝ์ด ๋ง๋ค.
