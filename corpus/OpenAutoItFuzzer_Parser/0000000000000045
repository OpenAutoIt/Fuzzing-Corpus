Func default_int($i = 0)
    ConsoleWrite($i)
EndFunc

Func default_string($s = "I Am a String")
    ConsoleWrite($s)
EndFunc

Func default_plus_expression($val = 3 + 3)
    ConsoleWrite($val)
EndFunc

; expect-stdout: "0"
default_int()
; expect-stdout: "123"
default_int(123)

; expect-stdout: "I Am a String"
default_string()
; expect-stdout: "A string"
default_string("A string")

; expect-stdout: "6"
default_plus_expression()
; expect-stdout: "19"
default_plus_expression(19)