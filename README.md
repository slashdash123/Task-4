# Task-4
UART (receiving and processing commands using RealTerm)

IMPORTANT Some variable declarations and function names are in my native language (Slovene). Reason being is, I did these assignments in the scope of my University. Hopefully the code will make sense, as I briefly explain the purpose of each task below.

This exercise consists of the implementation of an application that will receive a command (character string) via asynchronous serial communication UART, process it and send feedback back to the computer. For communication (sending and receiving) using RealTerm is recommended.

Command                       Action taken                Feedback message
-------------------------------------------------------------------------------
»L13o\n«                  LED turns on at PG13            »Green LED ON\r\n«
-------------------------------------------------------------------------------
»L13f\n«                  LED turns off at PG13           »Green LED OFF\r\n«
-------------------------------------------------------------------------------
»L14o\n«                  LED turns on at PG14            »Red LED ON\r\n«
-------------------------------------------------------------------------------
»L14f\n«                  LED turns off at PG14           »Red LED OFF\r\n«
-------------------------------------------------------------------------------
Anything else                       /                     »Unknown command\r\n«
-------------------------------------------------------------------------------

Tools used: STM32F429I discovery board (Cortex M4), breadboard, wires, 
