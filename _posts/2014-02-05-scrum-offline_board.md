---
layout: post
title: "[SCRUM] 오프라인 Kanban/Scrum 보드를 운영하는 이유"
---

현재의 팀으로 오기 전까지 있던 조직에서 Scrum, Kanban을 대대적으로 진행하고 있어요.   

제가 예전에 있었던 파트, 같이 일했었는데 지금은 다른 파트에 가신 분들과 이야기를 하다보면 Scrum과 Kanban이 개발에 도움이 되는게 아니고 그냥 일이 하나 더 생겼다는 말씀을 많이 하십니다.  

그래서 얘길 나눠봤는데 그런 이야기가 나오게 된 것중 가장 큰 부분이 **온라인으로 진행하는 Scrum** 인 것 같습니다.  

온라인으로 하면 좋은 점들이 물론 많죠.  

우리 회사에서 쓰는 JIRA는 올려둔 issue들을 사용해 바로 Scrum, Kanban 보드를 만들고 끌어올 수 있기 때문에 개발자들은 자리에서 바로 To do에 있던걸 Doing으로 옮길 수도 있고, Burndown chart도 시스템이 자동으로 그려주니깐 손으로 그릴 필요도 없구요.  
실시간으로 진척률이 보이니깐 윗분들이 관리하기에 더할 나위 없이 좋은 툴인 것 같아요.  

근데 저는 보통 오프라인 보드를 만드는 것을 권장합니다.  
제가 스크럼 마스터로 들어갈 때는 오프라인 보드를 반드시 만들구요. (저는 오프라인 예찬론자)  

그리고 그 보드를 복도에 걸어놔요. 오다가다 개발자들이 볼 수 있게요.  
하루에도 화장실을, 담배를 피우러 한시간에 한번씩 왔다갔다 할테니 오며가며 보드를 보면서  

**내가 지금 뭘 하고 있었는지, 뭘 끝냈고 오늘 뭘 더 해야하는지,**  
**내 옆사람이 지금 뭐때매 일 진행이 안되는지,**   
**난 다했는데 쟤 도와줘야지** 

라는 마음이 들도록이요.  
굳이 보드를 보려고 노력하지 않아도 그냥 눈에 보이니깐 자연스레 눈이 가는겁니다.  

아침마다 daily meeting을 보드 앞에서 하게되면 보드에 붙어있는 포스트잇을 보면서 자연스럽게 내가 어제 끝낸 일과, 오늘 할 일을 상기시켜서 말하게 됩니다.  
JIRA를 열어서 손바닥이든 종이에든 다시 한번 써와야 하고 무슨 말을 해야할지 생각하지 않아도 그냥 포스트잇을 보면 내가 뭘 할지, 어제 뭘 했는지가 자연스럽게 떠오르죠.  

그리고 한명씩 돌아가면서 얘기를 다 하고 나면 Burndown chart를 그리면서 지금 우리가 이번 Sprint를 완료하기 위해서 뭘 어떻게 할까에 대해서 다시 한번 생각하면서 daily meeting을 마무리 합니다.  

Daily meeting은 회의가 아니예요.  
한시간이 되면 그건 업무가 되니 Scrum도 Kanban도 곧 일이 되죠.   

아래 사진은 요즘 제가 운영하는 Kanban 보드인데요, PO라고 할 수 있는 조직 책임자 대상으로 진행하고 있어요.  

![Offline Kanban Board](/images/blog/offline_board.png)   

JIRA에 다 있는 것들인데 전부 포스트잇에 옮겨 적고, 아침에 30분씩 조직책임자들과 같이 앉아서 어제까지 붙였던 포스트잇에 대해 리뷰를 하고 새로운 업무를 분배합니다. 그리고 저는 다시 오늘 발생한 이슈들을 구분해서 각각 다른 색상의 포스트잇에 옮겨 적어 오프라인 보드에 붙이는거죠.  

아침저녁으로 progress를 체크하고 있는데, 물론 저것들을 매일 아침 적고 있고, 아침저녁으로 체크해서 옮겨 붙이려면 엄청 귀찮아요.  
각 조직책임자의 포스트잇은 해당 이슈를 실제로 처리하고 있는 개발자들이 올라와서 직접 업데이트 합니다. 누군가는 내용을 자세히 적어주기도 하고, 누군가는 status만 업데이트 해주기도 해요.  

**저는 그저 여기서 포스트잇을 칸반보드에 올려주고, Close되면 done으로 옮겨주는 것까지만 합니다.**  
**사람들이 스스로 할 수 있게끔 판을 깔아주고, 그것이 잘 돌아가는지 지켜보며, 잘 돌아갈 수 있도록 독려하는 역할을 하죠.**   

하지만 소규모 팀 단위로 진행할 땐 개발자 스스로가 자신이 하고있는 일을 직접 적고 progress를 직접 업데이트 하니까 시간은 daily meeting 15분이면 충분해요.   

그래도 귀찮다 하는 분들에게 제안하는 다른 방법은,  
온라인 스크럼보드 화면을 대화면 TV에 계속 띄워서 개발자들이 다니는 자리의 통로나 복도에 계속 띄워놓도록 가이드했습니다.  
그 이후에 실제로 그렇게 쓰시는 분들이 계시는데 실제 오프라인 보드처럼 자유롭진 않지만 온라인 보드를 쓸 때보단 대화가 훨씬 원활하게 많이 되는 것을 볼 수 있었습니다.   

사실 방법이 어떻게 됐든 단순히 Process 여서가 아니고 개발에 도움이 되는 방법이라면 오프라인이든 온라인이든 뭐든 좋다는 생각이예요.  

단순히 눈에 잘띄니까 KPI 관리를 하기 위해 도구로 사용되는 Scrum과 Kanban이 되지 않길 바라며.  

뿅-  