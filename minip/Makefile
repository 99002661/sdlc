PROJECT_NAME = Calci


BUILD = build


SRC = main.c\
src/src.c\


TEST_OUTPUT = $(BUILD)/Test_$(PROJECT_NAME).out

INC	= -Iinc

PROJECT_OUTPUT = $(BUILD)/$(PROJECT_NAME).out

$(PROJECT_NAME):all


.PHONY: run clean test  doc all

all: $(SRC) $(BUILD)
	gcc $(SRC) $(INC) -o $(PROJECT_OUTPUT).out

run:$(PROJECT_NAME)
	./$(PROJECT_OUTPUT).out



clean:
	rm -rf $(BUILD) $(DOCUMENTATION_OUTPUT)


$(BUILD):
	mkdir build
