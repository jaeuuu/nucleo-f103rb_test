# NUCLEO-F103RB Test Program

## 1. UART Test

### 1-1. Set debug port
- UART1 port used.
- _write() redefined. (```__attribute__((weak))``` function.)
- ```-u_printf_float``` added. (linker option for printf float type.)