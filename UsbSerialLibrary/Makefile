#ANDROID_HOME=~/apps/android-studio/sdk/

all: java_jar

java_jar: build
	mv ./build/bundles/release/classes.jar ./usb.jar

build: gradlew
	./gradlew build

clean:
	./gradlew clean

mrproper: clean
	rm -f ./usb.jar