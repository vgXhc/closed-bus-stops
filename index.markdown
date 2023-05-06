---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

Madison Metro's network is changing. On June 11, the redesigned network, with all new routes will start. This means a simpler network and faster service. 

It also means that a lot of stops will be closing. To help people navigate those closures, this is a volunteer effort to create and put up meaningful signage at the closed stops. Here's how it works:

1. You notice a stop closing sign in your neighborhood. 
2. Write down or take a picture of the 4-digit stop number.
3. Download the pdf file for that stop. 
4. Print the sign.
5. Install the sign at the bus stop.

Do not cover any signage for Metro. Don't put the signs up in a way that requires clean-up for Metro. Take extra care to put up the correct sign for the stop.

# The signs

Tip: (Use Ctrl-F to search for the stop number)

{% assign image_files = site.static_files | where: "pdf", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}





