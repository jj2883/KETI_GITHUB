KETI내 개발한 S/W 코드관리 방법


1) 개발자 별로 Branch 나눠서 개발
  - 개발자별: 개발 branch 1개, 누적 관리 branch 1개
  - 개발 branch 에서 개발 완료후 누적 branch로 merge 하여 관리

2) 개발한 S/W를 Tag별로 개별 버전 컨트롤
  - 수정한 코드가 있을 경우 새태그로 버저닝 관리

3) Tag에 관련 S/W 버전을 Release로 상세 관리
  - 개발이 중간 완료 / 최종 완료
  - 적용한/수정한 알고리즘 상세 설명
  - 버전관련 docker 및 환경 설명

![1_E4povWZ5H-K3OaguFQJ0IQ](https://user-images.githubusercontent.com/41278739/204170897-a38031a0-59df-430c-a794-83086403febc.png)

git clone
  - remote repository를 local repository에 저장
  
git add
  - 수정한 파일 local repository에 저장

git commit
  - 수정된 정보 local repository에 저장

git push
  - local repository를 remote repository에 저장
  
git fetch
  - local과 remote 파일 비교
  
git pull
  - remote repository와 local repository를 비교후 변경된 부분만 local에 저장
