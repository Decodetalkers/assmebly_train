cmake_minimum_required(VERSION 4.0.0)

project(train
  VERSION 0.1
  LANGUAGES ASM C
)

enable_language(ASM_NASM)

add_executable(hello
  hello.asm
)
