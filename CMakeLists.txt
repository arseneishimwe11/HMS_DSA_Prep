cmake_minimum_required(VERSION 3.31)
project(HMS)

set(CMAKE_CXX_STANDARD 20)

add_executable(HMS main.cpp
        Menu.cpp
        Menu.h
        Appointments/Doctor.cpp
        Appointments/Doctor.h
        Appointment/Appointment.cpp
        Appointment/Appointment.h
        Doctor/Doctor.cpp
        Doctor/Doctor.h
        Patient/Patient.cpp
        Patient/Patient.h
        utils/PatientsLL.h
        utils/Appointments.h
        utils/DoctorsLL.h
        utils/PatientsLL.h)
