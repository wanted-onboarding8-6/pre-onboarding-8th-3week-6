# π κ²μμ°½/κ²μμ΄ μΆμ² κΈ°λ₯ κ΅¬ν (6ν)

## π [λ°°ν¬μ£Όμ](https://pre-onboarding-8th-3week-6.vercel.app/)

</br>

## Team
<table>
  <tbody>
    <tr>
      <td align="center"><a href=""><img src="https://user-images.githubusercontent.com/107424974/212338752-939b2522-7b0a-4e7c-9ef4-85d957ec8f7c.jpeg" width="130px;" alt=""/><br /><sub><b>κ°νν</b></sub></a><br /></td>
      <td align="center"><a href=""><img src="https://user-images.githubusercontent.com/107424974/212338696-72b9433d-2ed5-4954-b9ce-ef444aa662eb.jpeg" width="130px;" alt=""/><br /><sub><b>κΉλ―Όμ </b></sub></a><br /></td>
      <td align="center"><a href=""><img src="https://user-images.githubusercontent.com/107424974/212338824-fc8fd767-7ed3-4600-9596-7665f823be03.jpeg" width="130px;" alt=""/><br /><sub><b>κΉμ’μ΄</b></sub></a><br /></td>
     <tr/>
      <td align="center"><a href=""><img src="https://user-images.githubusercontent.com/107424974/212338676-3e3b273b-5860-4eed-b971-1a26a9572e74.png" width="130px;" alt=""/><br /><sub><b>μ΄μν</b></sub></a><br /></td>
      <td align="center"><a href=""><img src="https://user-images.githubusercontent.com/107424974/212338768-2d0c7044-dc9e-4379-b9a9-bd7252e13287.png" width="130px;" alt=""/><br /><sub><b>μ΄μν</b></sub></a><br /></td>
      <td align="center"><a href=""><img src="https://user-images.githubusercontent.com/107424974/212338810-22a9d6cf-8073-45f5-a45a-a1025011d445.jpeg" width="130px;" alt=""/><br /><sub><b>μ΄μ‘°μ</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

#### π μΌμ  : 2023.01.10 - 01.13

</br>

## [κΈ°λ₯ μμΈ μν€ λ°λ‘κ°κΈ°](https://github.com/wanted-onboarding8-6/pre-onboarding-8th-3week-6/wiki)

1. [νλ‘μ νΈ μ€ν λ°©λ²](#νλ‘μ νΈ-μ€ν-λ°©λ²)
2. [κ΅¬νμ¬ν­](#κ΅¬νμ¬ν­)

</br>

## νλ‘μ νΈ μ€ν λ°©λ²

<br>

```bash
# yarn
yarn install
```

```bash
# local DB
yarn json-server --watch db.json --port 4000
```

```.env
REACT_APP_BASE_SEARCH_URL="http://localhost:4000/sick?q="
```

```bash
# start project
yarn start
```

<br>

## π  Used Tools

<div>
    <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=white"/>
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white"/>
    <img src="https://img.shields.io/badge/styled-components-DB7093?style=flat&logo=styled-components&logoColor=white"/>
    <img src="https://img.shields.io/badge/JsonServer-000000?style=flat&logo=JSON&logoColor=white"/>
    <img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=Vercel&logoColor=white"/>
</div>

<br>

## κ΅¬νμ¬ν­

1. μ§νλͺ κ²μμ API νΈμΆμ ν΅ν΄ κ²μμ΄ μΆμ² κΈ°λ₯ κ΅¬ν
   - μ¬μ©μκ° μλ ₯ν νμ€νΈμ μΌμΉνλ λΆλΆμ bold μ²λ¦¬
   - input focusμ localStorageλ₯Ό μ΄μ©ν΄ μ΅κ·Ό κ²μμ΄ λΈμΆ
   - μΌμΉνλ κ²μ κ²°κ³Όκ° μλ κ²½μ°μ UI νμ

</br>

2. API νΈμΆ μ΅μ ν
   - keyUp/keyDown eventλ₯Ό ν΅ν΄ μ¬μ©μμ ν€ μλ ₯μ΄ λλκ³  μΌμ  μκ° μ§μ°μκ°μ μ€ λ€, API νΈμΆμ ν΅ν΄ ν΄λΉνλ κ°μ λν μμ²­κ° λ°ν
   - λμ΄μ°κΈ°λ§ μλ string, μμ±λμ§ μμ λ¬Έμ(μμ λͺ¨μ λΆλ¦¬)μ κ²½μ° API νΈμΆμ νμ§ μλ λ±μ νΈμΆ μ‘°κ±΄ μΆκ°
   - CacheStorageλ₯Ό μ΄μ©ν΄ λμΌν μμ²­μ κ°μ μΊμλ₯Ό ν΅ν΄ λ°ν

</br>

3. ν€λ³΄λλ§μΌλ‘λ μΆμ²/μ΅κ·Ό κ²μμ΄λ‘ μ΄λ κ°λ₯
   - tabν€ or νμ΄ν λ°©ν₯ν€ μν μ‘°μμΌλ‘ μ΄λ κ°λ₯
   - μΆμ² κ²μμ΄λ‘ ν€λ³΄λ μ΄λ ν Enter μλ ₯ μ submit => μ΅κ·Ό κ²μμ΄ localStorageλ‘ μ μ₯
   - μΆμ² κ²μμ΄ λ§μ°μ€ ν΄λ¦­ μ, ν΄λΉ ν€μλλ₯Ό inputμ valueλ‘ μ΄λ

</br></br>

## λλ ν λ¦¬ κ΅¬μ‘°

```
π pre-onboarding-8th-3week-6
β£ π public
β£ π src
β   β£ π apis             # api νΈμΆ κ΄λ ¨
β   β£ π components       # component λͺ¨μ
β   β£ π hooks            # custom hook
β   β£ π image            # μ΄λ―Έμ§ νμΌλ€
β   β£ π lib              # fetch ν¨μ λλ ν λ¦¬
β   β£ π types            # type μ μ λͺ¨μ
β   β π util             # util ν¨μ λͺ¨μ
β π README.md            # README νμΌ
```
