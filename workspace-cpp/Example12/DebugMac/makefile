################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include src/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: ../../Binaries/Example12_DBG

# Tool invocations
../../Binaries/Example12_DBG: $(OBJS) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: MacOS X C Linker'
	gcc -L"/Users/nopper/workspace-cpp/GLUS/DebugMac" -L"/Users/nopper/workspace-cpp/External/mac/lib" -framework CoreFoundation -framework OpenGL -framework Cocoa -o "../../Binaries/Example12_DBG" $(OBJS) $(USER_OBJS) $(LIBS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(OBJS)$(C_DEPS)$(EXECUTABLES) ../../Binaries/Example12_DBG
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
