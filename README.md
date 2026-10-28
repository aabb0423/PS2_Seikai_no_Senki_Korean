# PS2_Seikai_no_Senki_Korean
PS2_Seikai_no_Senki_Korean
성계의 전기 PS2 한글 패치

1. ZIP을 폴더에 모두 풉니다.
2. Apply-Patch.bat를 실행하고 일본판 원본 ISO를 선택합니다.
   원본 ISO를 이 BAT 위로 끌어다 놓아도 됩니다.
3. 원본과 같은 폴더에 Seikai_no_Senki_Korean.iso가 생성됩니다.
4. PCSX2에서 생성한 ISO로 새로 부팅합니다. 기존 상태 저장은 불러오지 마세요.

대상: 일본판 SLPM-65937 / 2,056,159,232바이트
원본 SHA-256: d0e27f5fae9bae57f88bfd073864fbc1d70af032bf144afec4abbeb6798a7546
완성 SHA-256: 96ddcf864bf45d14af09826126d8dda584db3451f06a4b059e082f5e015dcd19

대사·선택지 15,569개, UI 문자열 447개, 이름/설정 718칸,
필수 UI 및 튜토리얼 이미지 87개를 적용했습니다.
이름 입력의 가나 문자표와 아브어 선택은 게임의 원래 기능입니다.
한국어 표시에는 설정의 한국어를 선택하세요.

Windows 10/11 x64용입니다. Python 설치는 필요하지 않습니다.
출력 ISO가 이미 있으면 덮어쓰지 않고 중단합니다.
명령줄: powershell -File Apply-Patch.ps1 -SourceIso "원본.iso" -OutputIso "새파일.iso"

xdelta 3.2.2: https://github.com/jmacd/xdelta (Apache-2.0)
MGalmuri: 동봉한 MGalmuri-OFL.txt 참고
