# Rune Factory 3 Unpack for Korean translation
Unpacked and modified Rune Factory 3 files for Korean Translation
 
Thanks to CUE for supporting `rf3Pack`

# 파일 종류
* `rf3Archive_Original` - 원본 룬팩토리 3(일판) rf3Archive.arc 파일 언팩본
* `rf3Archive_Modified` - 위 일판을 수정한 언팩본(그래픽만 수정함)
* `build.bat` - rf3Archive.arc 파일을 만들어주는 빌드 명령 실행파일
* `rf3Pack` - 룬팩토리 3 파일 패킹을 해주는 실행파일

# 파일 구조
* NFTR - 폰트 파일들 모음 0023이 메인폰트 0024가 서브폰트(아이템명 등에 사용) 0025는 GUI 내 사용자명 부분 등의 폰트
* TEXT - 말 그대로 텍스트 파일들 기본적으로 UTF-8 인코딩
* NCGR - 그래픽 파일들(대부분 번역 완료)
* NCLR - 팔레트 파일들
그 외에는 번역에 미필요한 파일들입니다.

# 빌드 방법
1. 먼저 [Tinke](https://github.com/pleonex/tinke)등의 프로그램으로 룬팩토리 3 파일을 연다
2. res\obj\rf3Archive.arc 파일을 찾아 `build.bat`파일과 동일한 경로에 놔둔 후, 이름을 `rf3Archive_Original.arc`로 바꾼다
3. 각종 수정된 텍스트, 폰트들을 `rf3Archive_Modified` 에 넣는다
4. `build.bat`을 실행해 rf3Archive.arc 파일을 만든다.
5. `Tinke`를 이용해 원본 룬팩토리 3(일판) 롬에 주입후 리빌드한다
6. 실행한다.

# 기타 해야되는 것들
* 인코딩에 맞는 커스텀 테이블 새로 제작하기
* 크리스탈타일2 내 프로그램 + NFTR Editor로 폰트 만들기
* 텍스트 재주입 하기
* 일부 그래픽(맵 처음진입시 나오는 그래픽 등) 찾은 후 번역하기