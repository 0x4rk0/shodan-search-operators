port -- Searches for a Specific Port (you can include multiple ports using commas (port:23,22,3389,6969))
org -- Searches for an Organization name and associated IPs, works best in quotes if there is white space! (org:"university of washington")
asn -- Searches for IPs associted with an Autonomous System (asn:AS###)
ip -- Searches for a Specific IP (ip:8.8.8.8)
net -- Seaches an IP Range (CIDR Range) (net:8.8.8.0/24)
has_screenshot:true|false -- Will search for IPs that Shodan has taken a screenshot of (org:"university of washington" has_screenshot:true)
http.title -- This will search for the HTTP title of a webpage (http.title:"Xfinity Home Router")
country -- This will search for IPs in a specific country using the countries 2 Digit ISO code (country:US)
state -- This will search for IPs in a specific State (I believe this only applies to US States)
city -- This will search for IPs in a specific city, best if used alongside country/state search fitlter (city:Seattle)
os -- Searches for a specific Operating System (os:"Linux 3.x")
product -- Searches for a specific Product (product:"Apache httpd")
tag -- This is an enterprise license search term, searches for tags applied by Shodan (tag:ics)

All of these filters can be inveresed by using "-"... (city:seattle -port:80,443,8080)