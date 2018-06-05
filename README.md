# iOS 12: What's new in XCTest 

## UI Tests

### XCUIElement | XCUIElementAttributes
* [ElementType](https://developer.apple.com/documentation/xctest/xcuielement/elementtype?changes=latest_minor)
* [SizeClass](https://developer.apple.com/documentation/xctest/xcuielement/sizeclass?changes=latest_minor)

### XCUIApplication
* [State](https://developer.apple.com/documentation/xctest/xcuiapplication/state?changes=latest_minor)

### XCUIDevice

Note: The XCUIDevice.Button.volumeUp and XCUIDevice.Button.volumeDown buttons are not available in the Simulator. Use *TARGET_OS_SIMULATOR* to check that your test is not running in the Simulator before calling these APIs.

* [Button](https://developer.apple.com/documentation/xctest/xcuidevice/button?changes=latest_minor)

### XCUIRemote
* [Button](https://developer.apple.com/documentation/xctest/xcuiremote/button?changes=latest_minor)

## Asynchronous Tests and Expectations

[Source](https://developer.apple.com/documentation/xctest/asynchronous_tests_and_expectations?changes=latest_minor)

* [XCTNSNotificationExpectation](https://developer.apple.com/documentation/xctest/xctnsnotificationexpectation?changes=latest_minor)

### XCTNSNotificationExpectation.Handler

A custom handler to be called when a matching notification is received.

[Source](https://developer.apple.com/documentation/xctest/xctnsnotificationexpectation/handler?changes=latest_minor)
