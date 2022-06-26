A voltage monitor for a 48 volt solar system which sends data to Thingspeak for remote access.
A voltage divider is used on the analog input of a Wemos D1 mini to measure the voltage which can rise as high as 68V.

It is intended to continue developing this simple monitor to control the charge cycle of Nickel Iron (NiFe) batteries. This is due to the lack of NiFe specefic chargers available on the market.
While lead acid and lithium battery chargers are common and in most cases can be made to "do the job", they are rarely ideal and often involve making compromises to the desired charge cycle of the NiFe batteries.
In my case, I have a Plasmatronics PL60 charge controller which is a first class charge controller but does not achieve and maintain a voltage high enough to initialize the NiFe batteries.
The intention is to use the Wemos D1 mini to read the voltage, current in and out, and control a SSR for the solar input. A single wire generator remote start may also be included.

