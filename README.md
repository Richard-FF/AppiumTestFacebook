# AppiumTestFacebook
A sample to test Facebook application with Appium on Android devices.
Steps:
1. Install Facebook application on your device and enable USB debug mode.
2. Connect your device to your PC, use adb to get udid of your device.
3. Open project with Eclipse.
4. Config following items in "testconfig.json" file which located in project root directory.
{
	"deviceName": "????????",
	"udid": "????????",
	"platformVersion": "????????",
}
5. Add your facebook username and password in "testdata.json" file which located in project root directory.
{
		"username": "????????",
		"password": "????????"
}
6. Run the test case as Junit or gradle test.
