# AI스쿨 리팩토링 과정 아카이브
AI스쿨 리팩토링 과정에서 수행한 프로젝트를 정리합니다.

## 📂 프로젝트 목록
### 1. dgrep.exe 악성코드 분석 보고서
> **핵심 요약:** dgrep.exe 악성코드 샘플 기초, 정적, 동적 분석 및 대응 방안 제시 보고서
 
**분석 대상**
 * 'dgrep.exe' (MD5 Hash: 68af0599e74d36bc2f39a2710754082c)

**주요 성과**
  * 기초분석(Virustotal)을 통해 악성코드 샘플의 위협 카테고리 식별
  * 정적분석(Exeinfo PE, PEiD, PEView)을 통해 패킹 여부 확인 및 언패킹 후 파일 문자열 분석
  * 동적분석(Process Explorer, Process Monitor, CurrPorts, Wireshark)을 통해 파일 실행 후 네트워크, 로컬 동작 분석
  * 분석을 바탕으로 악성코드 대응 방안 제시

**📄 보고서 보기:** [PDF 링크 클릭](https://github.com/doyoshigi/refactoring-course-ai-school/blob/main/%EB%A6%AC%ED%8C%A9%ED%86%A0%EB%A7%81_18%EC%A3%BC%EC%B0%A8_%EC%95%85%EC%84%B1%EC%BD%94%EB%93%9C%EB%B6%84%EC%84%9D%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)

### 2. Adobe_Acrobat_msetup_aVkyy.exe 악성코드 분석 & Snort 룰 개발 보고서 
> **핵심 요약:** Adobe_Acrobat_msetup_aVkyy.exe 악성코드 샘플 기초, 정적, 동적 분석 및 Snort 룰 설정
 
**분석 대상**
 * 'Adobe_Acrobat_msetup_aVkyy.exe' (MD5 Hash: 502db3fdcb1f401bab3247411e506457)

**주요 성과**
 * ANYRUN에서 악성코드 샘플 수집
  * 기초분석(Virustotal)을 통해 악성코드 샘플의 기초 정보(위협 카테고리, 파일 타입, 패킹여부, 관련 URL, 네트워크 활동 등) 분석
  * 정적분석(Exeinfo PE, PEiD, Bintext, PEView)을 통해 패킹 여부 확인 및 언패킹 후 파일 문자열 분석
  * 동적분석(Process Explorer, SmartSniff, CurrPorts, Wireshark)을 통해 파일 실행 후 네트워크, 로컬 동작 분석
  * 분석을 바탕으로 Snort 룰 설정 및 검증

**📄 보고서 보기:** [PDF 링크 클릭](https://github.com/doyoshigi/refactoring-course-ai-school/blob/main/%EB%A6%AC%ED%8C%A9%ED%86%A0%EB%A7%81_22%EC%A3%BC%EC%B0%A8_%EC%95%85%EC%84%B1%EC%BD%94%EB%93%9C%EB%B6%84%EC%84%9D%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)
