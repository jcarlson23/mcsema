foreach(
    example
    try_scheme
    factorial1
    factorial2
)
boost_add_executable(
    ${example}
    COMPILE_FLAGS
    "-I../.."
)
endforeach(
)
