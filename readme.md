# Awesome Israeli & Jewish Home Assistant Projects [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![haisrael](images/haisrael.png)

A list of Home Assistant integrations that are relevant for Israeli and Jewish users specifically (like Shabbat time listings etc)

## Contents

**Integrations, add-ons, components:**

- [Israel-Specific](#israel-specific	)
- [Jewish Interest](#Of-Jewish-Interest)

**Communities, discussion, inspiration:**

- [Communities and User Groups](#communities)
- [Blogs, Documentation](#documentation)

------


# [🇮🇱](https://emojipedia.org/flag-israel) Israel-Specific 

Home Assistant components and projects that are specifically relevant for people living in Israel.

## **[🚨](https://emojipedia.org/police-car-light) Red Alert (Tzeva Adom) Warning Integrations**

Integrations that work with Israel's national emergency warning system, operated by Pikud HaOref (Home Front Command). Note: the integrations are third-party projects and are not operated by Pikud HaOref. Test before relying upon these. 

- [RedAlert](https://github.com/idodov/RedAlert)  - This component is available from HACS. It creates configurable sensors for Red Alert warnings that can be used to drive automations, etc.
- [Oref Alert](https://github.com/amitfin/oref_alert)- Also available from HACS. Component works similarly. You can also create a testing sensor to verify that you have the alerts configured properly.

## Other Home Assistant Projects For Israeli Users

Other projects and components that may be of utility/interest:

- [Israel Meteorological Service (IMS) Weather Sensor](https://github.com/t0mer/ims-custom-component) - This sensor integrates with updates from Israel's national weather provider. 
- [Israeli School Vacation Days](https://github.com/rt400/School-Vacation) - This sensor checks whether it's a day off from school or not according to Israel's school calendar
- [Custom component for Electra air conditioners](https://github.com/yonatanp/electrasmart-custom-component) - An integration for Electra branded air conditioners

------


# [✡️](https://emojipedia.org/star-of-david) Of Jewish Interest

These projects might be of interest if you are Jewish (want Shabbat times through your HA instance, etc).

- [Jewish Sabbaths and Holidays](https://github.com/rt400/Jewish-Sabbaths-Holidays) - This is an incredibly helpful integration which uses the [HebCal API](https://www.hebcal.com/home/developer-apis) to expose times for Shabbat, Yom Tov and religious observance as sensors in Home Assistant.
- [Jewish Calendar](https://www.home-assistant.io/integrations/jewish_calendar/) - Home Assistant also ships with a 'Jewish Calendar' integration which provides sensors for the weekly Torah portion, the omer count, and even the Daf Yomi!
- [Molad sensor](https://github.com/chaimchaikin/molad-ha) - For exposing the Molad and Rosh Hodesh times as sensors in Home Assistant

------

## Communities 

- [Home Assistant Israel](https://www.facebook.com/groups/901600184564755) - Facebook group (in Hebrew) for Israeli Home Assistant users

------

## Documentation & Blog Posts

- I've written a few blogs about using the Jewish Sabbaths and Holidays sensor to drive automations. See, [this post](https://www.danielontech.com/an-easy-shabbat-automation-for-home-assistant/) for a start.
- [Example from the Home Assistant community forums](https://community.home-assistant.io/t/automating-an-entire-day/398731) of setting up automations for Shabbat observance.

------

## Other Israeli Open Source Projects & Resources

These repositories might also be of interest:

- [awesome-opensource-israel](https://github.com/lirantal/awesome-opensource-israel/tree/master)
- [Women Of Open Source Israel](https://github.com/lirantal/women-of-open-source-israel)
- [Israeli Open Source Companies](https://github.com/KaplanOpenSource/israeli-opensource-companies)
- [Robotics Open Source Israel](https://github.com/urig212/Robotics-Open-Source-Israel)
- [Israeli Government Open Source](https://github.com/IsraelGovernment/Israelopengov) 
- [Open source projects list](https://github.com/shlomizadok/open-source-il)
- [Kaplan Open Source Israel](https://kaplanopensource.co.il/open-source-in-israel/)





## Contribute

Check out the contribution guidelines or [email me](mailto:public@danielrosehill.com).
