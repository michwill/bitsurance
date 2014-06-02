bitsurance
==========

An experimental Blockchain insurance protocol

Version 0.1 

* Michael Ergorov (https://github.com/michwill)
* MacLane Wilkison (https://github.com/mswilkison)
* Eliot Weber (https://github.com/)
* Taariq Lewis (https://github.com/taariq)


Overview
--------

bitsurance is an experimental cyrpto-insurance protocol that enables the instant purchase of cryptographically-secured and financed insurance contracts covering some pre-specified event for which there is a provably trustless feed with which to measure binary outcomes. For illustrative purposes, we will assume the insurance being purchased is for protection against earthquakes, but the protocol may be generalizable to other forms of insurance.

Assumptions
-------------

Our claims are built on the following assumptions:

* We are able to identify a decentralized and provably trustless feed for earthquake events
* We are able to effecitvely price insurance coverage premiums in any chosen geographic location
* We are able to adequately and programmaitcally make appropriate insurance payments to the correct bitcoin address without a centralized system

What is Earthquake Insurance?
--------------------------

Earthquake insurance covers some of the losses and damage that earthquakes can cause to your home, belongings, and other buildings on your property. There are limits on what earthquake insurance pays. The purpose of earthquake insurance is to help put a roof back over your head. It does not replace everything you lost.[1](http://www.insurance.ca.gov/0100-consumers/0060-information-guides/0040-residential/earthquake-insurance.cfm)


Earthquake Contract Coins
--------------------------

Contracts are issued in the form of generic EarthquakeCoins. A customer may purchase an EarthquakeCoin by purchasing an annual Each Earthquake coin is issued as divisible up to eight decimal places and is redeemable for some agreed upon value in the event of an earthquake in a pre-specified location.


Decentralized claim filing after an earthquake
-----------------------------------------------

In order to validate a claim, redeemers must provide proof of claim via a [ZipCodeCoin/ZipCodeAddress/some other mechanism]. bitinsurance makes automatic decentralized bitcoin payments based on the following trustless measurements:

* Long/Lat of the epicenter of the earthquake
* Strength and duration of the earthquake
* Impact of strenght of earthquake on building structures

This decouples the value of an EarthquakeCoin from the identity of its owner, making EarthquakeCoins generic, fungible units and promoting a liquid secondary market while preventing bad actors from fraudulently claiming loss from multiple locations. To that end, each EarthquakeCoin may only be associated with one location to prevent anyone from inflating the value of their coins by associating them with payouts from multiple locations (for instance, by purchasing multiple ZipCodeCoins).

EarthquakeCoin Premium pricing
-------------------------------

The fee schedule will provide purchaser's with an estimate of the amount of EarthquakeCoins they should purchase in order to make themselves whole. This will vary with their location and subsequent risk exposure (since the
risk of loss from earthquakes is higher in Los Angeles than Nebraska, an individual in Los Angeles would likely purchase more EarthquakeCoins than her counterpart in  Nebraska). Payouts will be triggered when some condition
is met as determined by a trusted, 3rd party feed.

Earthquake Coverage Limits (Aftershocks) 
--------------------------
The protocol system will not offer new policies for any geographical location that has an earthquake and may be at risk for an ongoing period of aftershocks. The protocol will disable any new purchaes of EarthquakeCoins by a certain geographic location for a period of 1 week or 2 weeks.


Securing EarthquakeCoins
-------------------------

Premiums are used to purchase [GoldCoins or some basket of stable, inflation
resistant assets] which back the EarthquakeCoins and which are used to
finance any claims. The insurer's fee is [calculated as a percentage of
premiums/charged upon issuance of an EarthquakeCoin/determined via an
inflationary follow-on issuance of EarthquakeCoins].

EarthquakeCoins [expire/do not expire]. Coverage may be purchased on a
[monthly/biannual/annual] basis.
