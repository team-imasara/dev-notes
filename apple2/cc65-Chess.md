
## cc65?

- https://github.com/cc65/cc65
- "cc65 is a complete cross development package for 65(C)02 systems, including a powerful macro assembler, a C compiler, linker, librarian and several other tools."


## cc65-Chess

- https://github.com/StewBC/cc65-Chess

- 최근 컴파일러로 빌드하면 실행시 화면이 깨짐.
  - 아슬아슬하게 실행파일이 커서 HIMEM을 넘어가는 것인가
  - [x] old버전 cc65를 받아서 테스트 하자

- 이유는 아직 모르겠으나 구버전 cc65로 빌드하면 안 깨진다.
  - https://github.com/StewBC/cc65-Chess/issues/10
  - [cc65-Chess_patch-1_cc65_8e6c0c14_OK.dsk ](https://github.com/StewBC/cc65-Chess/files/13883531/patch-1_builds.zip) c65-Chess_patch-1_cc65_8e6c0c14_OK.dsk 는 문제없이 실행 가능함.
