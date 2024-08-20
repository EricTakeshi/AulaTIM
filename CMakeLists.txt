cmake_minimum_required(VERSION 3.15)

project(PWM_TIM4_Ch2 LANGUAGES C CXX ASM)

find_bsp(ID com.sysprogs.project_importers.stm32.cubemx SOURCE_PROJECT PWM_TIM4_Ch2.ioc)

add_bsp_based_executable(NAME PWM_TIM4_Ch2
	GENERATE_BIN
	GENERATE_MAP)

