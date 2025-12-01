# Compiler and flags
CXX = g++
CXXFLAGS = -Wall -Wextra -pedantic -std=c++17

# Source and targets
SRC1 = day_1.cpp
TARGET1 = day_1
SRC2 = day_1_part2.cpp
TARGET2 = day_1_part2

# Default rule: build both
all: $(TARGET1) $(TARGET2)

# Build day_1
$(TARGET1): $(SRC1)
	$(CXX) $(CXXFLAGS) -o $(TARGET1) $(SRC1)

# Build day_1_part2
$(TARGET2): $(SRC2)
	$(CXX) $(CXXFLAGS) -o $(TARGET2) $(SRC2)

# Clean up build files
clean:
	rm -f $(TARGET1) $(TARGET2)

# Run day_1
run1: $(TARGET1)
	./$(TARGET1)

# Run day_1_part2
run2: $(TARGET2)
	./$(TARGET2)
