Debug Bar Query Count Alert
===========================

Replaces the default text in the Debug Bar Plugin's Admin Bar button (which is "Debug Bar" by default in English) with the page's query count and total sql time. The button will be red if there were more than 200 queries or they took more than 1 second to run, and orange if the page required more than 100 queries or took more than 0.5 seconds to run.

Requires the [Debug Bar plugin](http://wordpress.org/plugins/debug-bar-console/) and for the constant `SAVEQUERIES` to be true.

Inspired by the Admin Bar on WordPress.com VIP, which offers similar functionality.

<img src="https://f.cloud.github.com/assets/465154/2058756/cb5f7c74-8b82-11e3-8227-5a9bb5d086b1.png" width="269" alt="Debug Bar Query Count Alert demo, normal state" /> &nbsp; <img src="https://f.cloud.github.com/assets/465154/2058757/cb68c978-8b82-11e3-9bb8-67ff4fb2bac6.png" width="269" alt="Debug Bar Query Count Alert demo, notice state" /> &nbsp; <img src="https://f.cloud.github.com/assets/465154/2058758/cb71f43a-8b82-11e3-9903-7a9fd7e1c3ad.png" width="269" alt="Debug Bar Query Count Alert demo, warning state" />
