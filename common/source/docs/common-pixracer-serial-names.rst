.. _common-pixracer-serial-names:

=======================
PixRacer Serial Mapping
=======================

Many different names are given to the serial hardware on PixRacer
where ArduPilot is concerned.  This document attempts to supply a
mapping between them.

+-----------+----------------+---------+-------------+------------+--------------+----------------+
| DataSheet | NuttX Userland | PX4_HAL | ParamPrefix | HW Label   | Def Role     | Notes          |
+===========+================+=========+=============+============+==============+================+
|           | ?              | ?       | \SERIAL0_   | USB        | Console      | Micro-USB Plug |
+-----------+----------------+---------+-------------+------------+--------------+----------------+
| UART4     | ?              | ?       | \SERIAL3_   | GPS        | GPS          |                |
+-----------+----------------+---------+-------------+------------+--------------+----------------+
| USART2    | ?              | ?       | \SERIAL1_   | TELEM1     | MAVLink      |                |
+-----------+----------------+---------+-------------+------------+--------------+----------------+
| USART3    | ?              | ?       | \SERIAL2_   | TELEM2     | MAVLink      |                |
+-----------+----------------+---------+-------------+------------+--------------+----------------+
| UART8     | ?              | ?       | \SERIAL4_   | GPS        | GPS          |                |
+-----------+----------------+---------+-------------+------------+--------------+----------------+
| UART7     | ?              | ?       | ?           | DEBUG      | Debug        |                |
+-----------+----------------+---------+-------------+------------+--------------+----------------+
| USART1    | ?              | ?       | ?           | ESP        | ESP8266      | bl serial      |
+-----------+----------------+---------+-------------+------------+--------------+----------------+
| USART8    | ?              | ?       | ?           | FRS        | FRSky        | invertible     |
+-----------+----------------+---------+-------------+------------+--------------+----------------+
