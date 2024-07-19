<div align= "center">
    <img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&height=180&text=Hello%20World!&animation=fadeIn&fontColor=ffffff&fontSize=70" />
    </div>
    <div align= "center"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🐶개발환경 </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: center; color: #282d33;"> </li>컨트롤 노드 : <b>Ubuntu</b></div><div>제어노드 : <b>Ubuntu</b></div>
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
        <img src="https://github.com/user-attachments/assets/481ccf09-913b-4df1-afbc-11a7dab2f2e2">
    </div> 
    <div align= "center"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🌹기능설명 </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: center; color: #282d33;">
  <h3>1. Bastion 서버 로드 밸런싱</h3>
  <details>
      <h5>Bastion을 타겟 그룹으로 설정 한 로드 밸런서 IP 접속</h5>
      <img src="https://github.com/DevelopIsHobby/CCCR_Terraform/assets/107912101/e8088f9a-d451-4a5f-bca0-c12a3c3102d7"width="700" height="150" ><br><br>
      <img src="https://github.com/DevelopIsHobby/CCCR_Terraform/assets/107912101/480744e8-7e74-4d9e-9ff7-78ff1ee81c70"width="700" height="150" >
    </details>

   <h3>2. Web 서버 로드 밸런싱</h3>
      <details>
      <h5>Web을 타겟 그룹으로 설정 한 로드 밸런서 IP 접속</h5>
      <img src="https://github.com/DevelopIsHobby/CCCR_Terraform/assets/107912101/f0bd6648-89fd-41f2-ac7e-f33d49e74d3a"width="700" height="150" ><br><br>
      <img src="https://github.com/DevelopIsHobby/CCCR_Terraform/assets/107912101/0e324127-7626-4fbd-a1e0-5ccdd3418a8a"width="700" height="150" ></details>
      
  <h3>3. RDS Replica</h3>
    <details>
      <h5>RDS가 정상적으로 생성되었는지 확인</h5>
      <img src="https://github.com/DevelopIsHobby/CCCR_Terraform/assets/107912101/4c07a473-d390-4e36-9104-70431a8c9ff6"width="900" height="100" ><br><br>
      <img src="https://github.com/DevelopIsHobby/CCCR_Terraform/assets/107912101/b7183f78-7087-47be-9298-765d13c5ea7e"width="900" height="100" >
      <h5>Replica 생성 확인</h5>
      <img src="https://github.com/DevelopIsHobby/CCCR_Terraform/assets/107912101/57fe02c9-b9ed-4f03-afd0-fae5cd601e24"width="900" height="130" ></details>

   <h3>4. AutoScaling</h3>
      <details>
        <h5>오토스케일링 그룹 확인</h5>
        <img src="https://github.com/DevelopIsHobby/CCCR_Terraform/assets/107912101/7f044f14-ba23-44af-b56a-49d93b8dcc9a" width="900" height="250">
        <h5>4개의 인스턴스 추가(오토스케일링 그룹 희망 용량 1로 설정)</h5>
        <img src="https://github.com/DevelopIsHobby/CCCR_Terraform/assets/107912101/016f64c7-5730-47f2-aa96-8db822fec604" width="800" height="350"><br>
      </details>

   </div>
   </div> 
    </div>
    <div align= "center">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ Tech Stacks </h2> <br> 
    <div style="margin: 0 auto; text-align: center;" align= "center">
          <img src="https://img.shields.io/badge/Linux-FCC624?style=plastic&logo=Linux&logoColor=black">
          <img src="https://img.shields.io/badge/Terraform-623CE4?style=plastic&logo=Terraform&logoColor=white">
          </div>
    </div>
<div align="center">
  <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;">😃 소감 🥲</h2>
    :star:AWS 콘솔에서 일일히 만들고 지워야 했던 것에 비해 매우 편리하게 서비스를 구성할 수 있었다.<br>
    :sweat_drops:모듈을 좀 더 세분화 할 수 있었다면 좋았을 것 같다.<br>
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
