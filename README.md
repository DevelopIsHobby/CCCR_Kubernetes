<div align= "center">
    <img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&height=180&text=Hello%20World!&animation=fadeIn&fontColor=ffffff&fontSize=70" />
    </div>
    <div align= "center"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🐶개발환경 </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: center; color: #282d33;"> </li>컨트롤 노드 : <b>Ubuntu</b></div><div>제어노드 : <b>Ubuntu</b></div><div>쿠버네티스 : <b>Kubespary</b></div>
    </div>
    <div align= "center"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🧸구현 기능 </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: center; color: #282d33;">
    <i>NFS Storage(Dynamic Provisioning)</i><br>
    <i>Dockerfile 활용 워드 프레스 이미지 직접 생성</i><br>
    <i>StatefulSet 활용 DB 이중화</i><br>
    <i>Ingress & AutoScaling 구현</i><br>
   </div> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;">  :paw_prints: 아키텍처 </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: center; color: #282d33;">
        <img src="https://github.com/user-attachments/assets/481ccf09-913b-4df1-afbc-11a7dab2f2e2" width="1200" height="500" >
    </div> 
    <div align= "center"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🌹기능설명 </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: center; color: #282d33;">
  <h3>1. DB 이중화</h3>
  <details>
      <h5>읽기 복제본에 "hello mysql"이 동기화 됨</h5>
      <img src="https://github.com/user-attachments/assets/d12fd0e6-c1d0-4680-8c64-bd577c8133c7" width="800" height="400" >
      <h5>읽기 복제본에 워드프레스 데이터베이스 저장</h5>
      <img src="https://github.com/user-attachments/assets/7430f10d-6ec2-40c0-a02f-ae745decc62f"width="600" height="650" >
      <h5>읽기 복제본에 워드프레스 사용자 저장</h5>
      <img src="https://github.com/user-attachments/assets/68abc701-eeff-4e0b-bed9-4fb9c22fe922"width="400" height="250" >
    </details>

   <h3>2. 도커에서 워드프레스 이미지 생성</h3>
      <details>
      <h5>도커 이미지 생성 후 도커 허브에 저장</h5>
      <img src="https://github.com/user-attachments/assets/b293f982-c7ad-48b9-be95-e72673d75c6c"width="700" height="100" ><br>
      <img src="https://github.com/user-attachments/assets/c9bde1ad-2fc7-49d3-aff8-2fd6356de84a"width="700" height="170"><br>
      <img src="https://github.com/user-attachments/assets/27fe1706-c628-4bfd-8bf2-0f2f49733728"width="700" height="500" >
      <h5>도커 컨테이너 실행</h5>
      <img src="https://github.com/user-attachments/assets/c6e0cd8d-91d3-4650-a644-199da7eca85d"width="1200" height="100" ><br>
      <img src="https://github.com/user-attachments/assets/39d9df61-4429-453c-8e4b-f005a0e6f402"width="600" height="650" >
     </details>
      
  <h3>3. 쿠버네티스에서 워드프레스 구현</h3>
    <details>
      <h5>파드</h5>
      <img src="https://github.com/user-attachments/assets/d3ffab01-6c8a-4adb-a8ef-5eb671dac270"width="650" height="200" >
      <h5>서비스</h5>
      <img src="https://github.com/user-attachments/assets/2c45172d-2e1d-4585-a89b-798a42413488"width="600" height="150" >
      <h5>워드프레스</h5>
      <img src="https://github.com/user-attachments/assets/7ade152a-7862-488c-b7fb-722d459d6799"width="600" height="650" ></details>

   <h3>4. Ingress 서비스</h3>
      <details>
        <h5>인그레스 생성 확인</h5>
        <img src="https://github.com/user-attachments/assets/cfebb7e5-6ee0-4746-957e-b81fbcdabbcf" width="650" height="350">
        <h5>인그레스 동작 확인</h5>
        <img src="https://github.com/user-attachments/assets/61d58cd4-92b5-43f9-9cd2-2576fd27dd4c" width="650" height="400"><br>
      </details>
      
   <h3>5. AutoScaling 구현</h3>
      <details>
        <h5>HPA 생성 확인</h5>
        <img src="https://github.com/user-attachments/assets/2183d896-0d41-4c3b-9034-33a704fd114f" width="650" height="70">
        <h5>오토스케일링 동작 확인</h5>
        <img src="https://github.com/user-attachments/assets/000ba7ca-6944-477e-8ee6-b597ce6b2d70" width="650" height="160"><br>
        <img src="https://github.com/user-attachments/assets/b5d28dcf-7781-4fa4-bfa0-9fc2a60a1935" width="650" height="600">
      </details>

   </div>
   </div> 
    </div>
    <div align= "center">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ Tech Stacks </h2> <br> 
    <div style="margin: 0 auto; text-align: center;" align= "center">
        <img src="https://img.shields.io/badge/Ubuntu-E95420?style=plastic&logo=Ubuntu&logoColor=white">
        <img src="https://img.shields.io/badge/Kubernetes-326ce5?style=plastic&logo=Kubernetes&logoColor=white">
          </div>
    </div>
<div align="center">
  <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;">😃 소감 🥲</h2>
    :star:도커를 이용해서 워드프레스를 구축하는 이미지를 생성해 볼 수 있었다.<br>
    :star:쿠버네티스 이미지에 이미 파일이 존재할 때 PVC가 마운트 되면서 빈 디렉토리로 덮어씌워지는 현상을 해결할 수 있었다.<br>
    :star:오토스케일링을 구현할 수 있었다.<br>
</div>


<div align= "center">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🧑‍💻 Contact me </h2> <br> 
    <div align= "center"> 
        <a href="https://github.com/DevelopIsHobby"> 
            <img src="https://img.shields.io/badge/GitHub-ffffff?style=plastic&logo=GitHub&logoColor=black&link=https://github.com/DevelopIsHobby"> 
        </a>
        <a href=https://www.notion.so/05ab0f771bb5433faebb8061defc48c4?pvs=4> <img src="https://img.shields.io/badge/Notion-000000?style=plastic&logo=Notion&logoColor=white&link=https://www.notion.so/05ab0f771bb5433faebb8061defc48c4?pvs=4"> </a>
          </div>  <br> 
    <div align= "center">  </div> 
</div>
