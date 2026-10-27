# Decisions

Key product decisions for v1, and why. When a decision changes, update it here and add the date.

| # | Question    | Decision                   | Why         |
| - | ----------- | -------------------------- | ----------- |
| 1 | When does the next name unlock?        | At local sunrise each day, based on the user's location (changed from Fajr, 28 Oct 2026).     | Starts the day with the name; simpler than Fajr, with no calculation method to choose.        |
| 2 | Personal journey or shared calendar?         | **Personal journey**. Everyone starts at name 1 when they install.   | The names are learned in order, at each person's own pace. |
| 3 | Can users go back to past names?          | **Yes, inside the app.** Future names stay locked. The widget and wallpaper always show today's name.       | Revisiting helps retention; the widget stays focused on one name.     |
| 4 | What happens on missed days?          | Names advance by calendar. A new name unlocks at every sunrise whether or not the app is opened. The app always opens on today's name; skipped names stay available as past names.       | Requiring the user to open the app to unlock would be annoying, and the widget and wallpaper need to update on their own.     |
| 5 | What happens after day 99?          | All names stay unlocked to browse freely. The user can also restart the journey from name 1.       | Lets people keep learning without losing access.     |
| 6 | Which list of 99 names?          | The list in Allah by Yasin T. al-Jibouri, ["Ninety-Nine Attributes of Allah".](https://al-islam.org/allah-yasin-t-al-jibouri/ninety-nine-attributes-allah#attributes-allah)       | Lists differ slightly between sources, so the app uses one stated source.     |
| 7 | Business model?          | **Free**. Donations may be added later. No ads.       | 	Sadaqah jariyah; keeps the experience calm.     |