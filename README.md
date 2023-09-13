# upeth

> upeth는 upbit 클론 코딩 프로젝트입니다 (22.02.27 - 22.04.28)

https://upeth-client.vercel.app<br>
이 프로젝트는 Vercel에 의해 배포되었습니다

## Tech Stack

`JavaScript` `React` `Next.js` `Emotion` `MobX` `React Query` `Next Auth` `vercel`

## Feature

- 실시간 가격과 거래량 등의 데이터 렌더링
- 실시간 호가창과 거래내역 렌더링
- 해외 거래소 데이터 렌더링
- 차트 렌더링
- 코인 검색 기능
- 관심 코인 선택 기능
- Github으로 로그인 기능

## 로그인
![](https://github.com/royalbluee/upeth-client/blob/main/wiki_images/Login.gif)<br>
Next Auth를 사용하여 OAuth기반의 로그인 방식 구현했습니다.

## Tab 전환
![](https://github.com/royalbluee/upeth-client/blob/main/wiki_images/Tab.gif)<br>
전역 상태로 Tab 메뉴를 관리하여 전환되는 메뉴에 따라 코인 데이터를 API로 가져와 출력합니다.

## 관심종목
![](https://github.com/royalbluee/upeth-client/blob/main/wiki_images/Favorite.gif)<br>
Local Storage를 이용하여 관심종목을 관리합니다.

## 정렬
![](https://github.com/royalbluee/upeth-client/blob/main/wiki_images/Sort.gif)<br>
전역 상태로 정렬 기준을 관리하여 기준에 맞춰 정렬 후 코인 데이터를 출력합니다.

## 검색
![](https://github.com/royalbluee/upeth-client/blob/main/wiki_images/Search.gif)<br>
전역 상태로 검색 키워드를 관리하여 키워드에 따라 필터링 후 코인 데이터를 출력합니다.

## 코인 데이터 전환
![](https://github.com/royalbluee/upeth-client/blob/main/wiki_images/CoinData.gif)<br>
해당 URL에 맞는 코인 데이터를 출력합니다.

## 차트
![](https://github.com/royalbluee/upeth-client/blob/main/wiki_images/Chart.gif)<br>
HighChart를 사용하여 차트를 출력합니다.

## 실시간 오더북과 거래내역
![](https://github.com/royalbluee/upeth-client/blob/main/wiki_images/Orderbook.gif)<br>
해당 코인 오더북과 거래내역 데이터를 WebSocket을 통해 실시간 데이터를 받아 출력합니다.

## Scripts

npm run dev

## env

GITHUB_CLIENT_ID<br>
GITHUB_CLIENT_SECRET<br>
NEXTAUTH_SECRET<br>
