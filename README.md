# location_tracker

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.


- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


##Mobile
Need to develop Location screen within Flutter framework:
1) From Menu, click on Attendance - it will load a list of members with 2 icons on the
right side. The 2nd icon is to check the current Location & Route traveled by an
individual member.
2) When you see any individual member data (by clicking on the icon), it will show the
current location on MAP. And in bottom - it shows all the visited locations in timeline
view. By default, it shows TODAY's data - date filter will help to see past dates data. You
can pull the list above to see the complete list of traveled locations.
3) Any 2 visited locations will generate a route which can be seen on the next screen. It
shows Start Location, Stop Location, Total KMs & Total Duration traveled. On the
bottom (map screen), it shows the complete route drawn on Google Map. The red dots
on the route line shows STOP time (so if a user has stopped for more than 10 min
anywhere while traveling, it will count as STOP time).
