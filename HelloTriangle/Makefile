CFLAGS = -std=c++17 -O2
LDFLAGS = -lglfw -lvulkan -ldl -lpthread -lX11 -lXxf86vm -lXrandr -lXi

VulkanStudy: main.cpp
	g++ $(CFLAGS) -o VulkanStudy main.cpp $(LDFLAGS)

.PHONY: test clean

study: VulkanStudy
	./VulkanStudy

clean:
	rm -f VulkanStudy
