## 프로젝트 입문 과제_git 학습 

**git이란? : 버전 관리 시스템 (vcs)으로, 프로젝트 협업 관리 도구로써 사용**

**git의 장점**
 * 여러 명이 프로젝트를 병렬 처리 - 빠른 개발 속도
 * 포트폴리오 관리 용이
 * 로컬 서버로서의 기능
 

**git 문법 - 명령어 (긴 옵션은 -- 짧은 옵션 -)**
 * config - 환경설정(name, email, etc..)
   *--global 옵션으로 특정 프로젝트가 아닌 전체에 적용..
 * clone - 원격 저장소의 repository를 로컬에 복사
 * add name - name 파일을 프로젝트에 추가
   * add . - 파일 전체 추가
 * commit  - 파일의 업로드 등 시점을 기록( 특정 시점으로의 복구 등 기능)
   *-m 옵션으로 메세지 추가
 * push - 로컬의 commit 된 내용을 원격저장소에 출력
 * branch
   * branch name - name 이름의 branch 생성
   * checkout name - name branch로의 변경
   * merge name - name branch를 master(main) branch에 병합
 * push - commit된 내용들을 원격 저장소로..\

**유의사항**
  * merge 시의 충돌 - 충돌 파일에 직접 찾아가서 오류 해결 후 커밋
  * master 이외 branch에서 push - --set-upstream origin branch

**앞으로 해야할 부분들** 
  * 쉘 명령어 학습(텍스트 편집기 등)
  * 개념 숙지
  * 실제적인 사용

~~~C++
#include<iostream>
using namespace std;
int main()
{
	cout<<"소스코드 작성 예시"<<'\n';
	return 0;
}
~~~
[HICC](https://github.com/HICC-Introduction)
~~시작이 반~~





	
