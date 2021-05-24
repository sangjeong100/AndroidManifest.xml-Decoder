# AndroidManifest.xml-Decoder
AndroidManifest.xml decoder


## 개요
- 안드로이드 소스 코드를 apk 추출하면, 핵심 파일인 AndroidManifest.xml파일이 encoding된다. 
  이에 따라서 해당 프로젝트는 AndroidManifest.xml의 특징을 이용해서 AndroidManifest.xml 파일을 자동으로 Decoding하는 프로젝트이다.

## AndroidManifest.xml 특징
![image](https://user-images.githubusercontent.com/56123201/119329385-1f4fd380-bcc0-11eb-8c5d-2e1ee7f82fe1.png)
- AndroidManifest.xml은 위와 같은 구조로 되어있으며, 전체 chunk의 header부터 string pool chunk, namespace chunk, element chunk로 이루어져 있다. 
