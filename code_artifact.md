# 2026 장아초 주간업무 및 월중행사 시스템 웹사이트 무료 배포 가이드

본 프로그램은 단일 HTML 파일(`index.html`)로 구성되어 있어, 무료 웹 호스팅 서비스를 이용하면 **1분 만에 누구나 접속 가능한 인터넷 사이트**로 배포할 수 있습니다. 

가장 쉽고 추천하는 2가지 방법을 안내해 드립니다.

---

## 방법 1. Netlify (가장 쉽고 빠른 방법 - 추천 ⭐⭐⭐⭐⭐)

별도의 복잡한 설정 없이 `index.html` 파일을 드래그 앤 드롭하는 것만으로 인터넷 주소가 생성됩니다.

1. **Netlify 가입**: [https://www.netlify.com](https://www.netlify.com) 접속 후 회원가입 (Google 계정 등으로 간편 가입).
2. **Sites 메뉴 이동**: 로그인 후 상단 메인 화면의 **Sites** 탭 클릭.
3. **파일 업로드**:
   - 오른쪽 우측 화면에 있는 **"Browse to upload"** 영역이나 **"Drag and drop your site folder here"** 영역에 작성된 `index.html` 파일(또는 해당 파일이 담긴 폴더)을 마우스로 끌어다 놓습니다.
4. **배포 완료**:
   - 몇 초 뒤 `https://random-name-12345.netlify.app` 형태의 도메인 주소가 자동 생성됩니다.
5. **주소 변경 (선택사항)**:
   - **Site configuration** > **Change site name** 메뉴에서 `jangah-2026.netlify.app`과 같이 학교에 맞는 깔끔한 주소로 변경할 수 있습니다.

---

## 방법 2. GitHub Pages (정석적이고 안정적인 방법 ⭐⭐⭐⭐)

세계 최대 개발 플랫폼인 GitHub를 이용한 무료 지속 호스팅 방식입니다.

1. **GitHub 가입 및 접속**: [https://github.com](https://github.com) 가입 및 로그인.
2. **새 저장소(Repository) 생성**:
   - 우측 상단 **`+`** 버튼 클릭 -> **New repository** 선택.
   - **Repository name**에 `jangah-2026` 입력.
   - **Public**으로 선택 후 **Create repository** 클릭.
3. **파일 업로드**:
   - 생성된 페이지에서 **"uploading an existing file"** 링크 클릭.
   - 오른쪽 우측에 `index.html` 파일 업로드 후 하단 **Commit changes** 클릭.
4. **GitHub Pages 활성화**:
   - 상단 **Settings** 탭 -> 좌측 메뉴에서 **Pages** 클릭.
   - **Build and deployment** 하단의 `Branch` 설정을 `None`에서 **`main`** (또는 `master`)으로 변경하고 **Save** 클릭.
5. **배포 완료**:
   - 약 1~2분 후 `https://사용자아이디.github.io/jangah-2026/` 형태의 전용 사이트 주소가 생성됩니다.

---

## 💡 선생님/교직원 간 공유 팁
- **URL 단축 서비스**: 생성된 긴 사이트 주소를 [https://bit.ly](https://bit.ly) 나 [https://han.gl](https://han.gl) 등에서 `bit.ly/장아초2026` 처럼 짧은 주소나 QR코드로 변환하여 교직원 카톡방이나 안내장에 공유하시면 더욱 편리합니다.
- **데이터 저장 안내**: 본 프로그램의 데이터는 개별 브라우저(LocalStorage) 및 CSV 내보내기/불러오기로 관리되므로 서버 비용이 전혀 발생하지 않습니다.