This repository contains the customer-facing Zalt mobile app, which was written with the new Flutter framework for cross-platform native mobile development.  This app communicates with our custom-built Zalt API.

==

Zalt is B2B enterprise software that digitizes the customer experience of non-tech businesses (such as apartment buildings) by allowing those businesses to easily create customizable, customer-facing, mobile micro-apps without any technical expertise. For instance, just through several taps within Zalt’s mobile app, residents of an apartment can request services, make payments, submit forms, chat with employees, schedule appointments, and more. Additionally, Zalt automates the workflow of employees of the apartment by storing and updating residents’ data in real-time, allowing effortless data exportation to industry-standard formats such as Excel, and more. 

Furthermore, Zalt strives to increase the engagement and sales of the services of an apartment building by using computational marketing techniques; our microapp strategy allows us to use machine learning to build an accurate profile of the apartment residents to determine whom would be most optimal to target with promotions and the types of promotions to use.

Some of the features Zalt provides are as below:

custom form submission platform (customer to business), instant-messaging platform (between business and customer), a zero-hardware payment platform, appointment scheduling platform, notification platform, and customer feedback platform, and login platform.

Some of the Flutter packages I used are as below:

- `image_picker` for uploading images from image library and taking photos with camera
- `add_2_calendar` for adding events to each platform’s default calendar
- `qr_mobile_vision` for reading and scanning QR codes
- `stripe_payment` for credit card UI
- `geolocator` for obtaining the current location of the mobile device
- `signature_pad` for finger (signature) detection and image exportation of the result
- Firebase cloud messaging for receiving push notifications
- `flutter_google_places` for Google places autocomplete
- `json_annotation` for JSON serialization and deserialization
- `datetime_picker_formfield` for allowing users to select date and time in a form
