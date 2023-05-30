make: 
	as -g -o main.o main.S
	ld --oformat binary -o main.img -T link.ld main.o
	qemu-system-x86_64 --drive file=main.img,format=raw,index=0,media=disk


clean:
	rm *.o 
