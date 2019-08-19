# git-release

## 사용 방법

1. 클론하세요.

2. PATH에 git-release 디렉토리를 추가하세요.

3. 사용법: git-release [-v | --version] [-h | --help] [-M | --major] [-m | --minor] [-p | patch]

## 옵션 설명

`[-M | --major]`

유의적 버전 (Semantic Versioning)에 따라 Major 버전을 1 올립니다.

v**1**.2.3 → v**2**.0.0

`[-m | --minor]`

유의적 버전 (Semantic Versioning)에 따라 Minor 버전을 1 올립니다.

v1.**2**.3 → v1.**3**.0

`[-p | patch]`

유의적 버전 (Semantic Versioning)에 따라 Patch 버전을 1 올립니다.

v1.2.**3** → v1.2.**4**