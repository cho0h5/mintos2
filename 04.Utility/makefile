all: ImageMaker

ImageMaker:
	@echo
	@echo ======== ImageMaker Build Start ========
	@echo
	
	make -C 00.ImageMaker
	cp 00.ImageMaker/ImageMaker ../ImageMaker
	
	@echo
	@echo ======== ImageMaker Build Complete ========
	@echo


clean:
	make -C 00.ImageMaker clean
	rm -f ../ImageMaker
