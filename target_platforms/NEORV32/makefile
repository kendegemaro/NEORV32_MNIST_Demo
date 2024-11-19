# Modify this variable to fit your NEORV32 setup (neorv32 home folder)
# This has to be set to your path!
NEORV32_HOME ?= /home/kende/Schreibtisch/neorv32-main

# User's application sources (add additional files here)
APP_SRC = MNIST_NeuralNet_test_suite.c MNIST_NeuralNet.c include/k2c_activations.c include/k2c_core_layers.c include/k2c_helper_functions.c 

# User's application include folders (don't forget the '-I' before each entry)
APP_INC = -I . -I ./include

# Override the default CPU ISA
MARCH = rv32i_zicsr_zifencei_zfinx

include $(NEORV32_HOME)/sw/common/common.mk