# Hard_1600_MonkeyWantToBeHorse

1600 말이 되고픈 원숭이

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/Hard_1600_MonkeyWantToBeHorse/blob/main/1600_pro.PNG)

## What Algorithm should I use?

Graph Algorithm ,bfs

## What was the key point and the hard part?

이거는 한국말로 쓰는게 나을거 같아서 한국어로 적는다.

맨 처음 생각은 당연히 bfs를 돌려서 말처럼 움직일 수 있는 경우와 원숭이 처럼 움직이는 모든 경우의 수를 큐에 넣고 진행 하였다.

하지만 틀렸습니다를 보고 내가 도저히 뭘 잘 못했는지 모르겠어서 여기 저기 찾아 보게 되었다.

여기서 다들 하는 말이 말로 움직여서 특정 장소에 도착한거랑 원숭이 처럼 움직여서 특정 장소에 움직인 거랑 달라요! 라는 말이다.

이 말이 잘 이해가 안되서 내가 이해한 말을 자세히 써보기로 했다.

만약 지금 말처럼 이동할 수 있는 기회가 한번인 경우에 그 한번의 기회를 사용해서 (x,y)에 가는 case가 만약 원숭이 처럼 움직여서 (x,y)에 가는 경우와 같은 이동횟수에 있다면 당연히
원숭이 처럼 움직여서 갈 것이다. 특히나 결슴점이 (x,y)에서 말처럼 이동하면 바로 (H,W)에 갈 수 있는 경우이면 말이다.

처음에는 이러한 상황 자체가 불가능 하다고 생각했는데 만약 K가 크고 말처럼 이동할때 여러 방향으로 왔다 갔다 거리면 일어날 수 있는 상황이다.

따라서 우리는 원숭이 처럼 움직여서 (x,y)에 가는 경우가  말처럼 이동할 수 있는 기회가 한번인 경우에 그 한번의 기회를 사용해서 (x,y)에 가는 경우보다 늦게 계산되어 
visit[x][y] 가 true가 되어서 전자의 경우가 q에 들어가지 못하는 경우를 막기 위해 3차원 배열을 써서 visit을 판별하는 것이다.


## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
