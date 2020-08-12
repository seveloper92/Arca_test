# Arca_test

ARCA 라이브러리란?
Application Crash Report for Android 로 안드로이드 앱 다운시 에러 정보를 표시해주는 라이브러리 이며,
현재 1만3천개 앱에서 사용중인 공신력있는 라이브러리입니다.

Git URL: https://github.com/ACRA/acra/

ARCA라이브러리가 지원하는 에러의 전달 방식으로 Email, 자체서버, 앱단 경고 다이얼로그 가 있으며,  현재 Expresso에는 서버전송과 Crash 발생시 안내 다이얼로그를 적용하였습니다.
단순 에러 발생지점 외에 앱의 이름과 버전정보, 단말기 정보 또한 포함되어 있으며 추후 전체 서버에 적용 된다면 이슈를 알아가는데 많은 도움이 될 것으로 생각됩니다.

ARCA 리포트 지원 타입
 

[Acra 적용내역]

-	@AcraHttpSender  App Crash 발생시 서버로 기기정보 및 에러정보 전송 
-	@AcraDialog  App Crash 발생시 안내 다이얼로그 적용

