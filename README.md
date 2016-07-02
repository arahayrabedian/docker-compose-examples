# docker-compose-examples
This is sample code to accompany a blog post as samples

All folders correspond to a blog post's code, except double_advanced_working, which 
is a working example (but lacking environment variables)

##`single_simple`
basic intro to docker-compose, a single webapp running a single stack, a sample, not runnable

##`single_intermediate`
a slightly more complex intro to docker-compose, introduces environment variables

##`double_advanced`
an example that tosses in a reverse proxy on top of two webapp stacks

##`double_advanced_working`
a **working** example that demonstrates working use of a reverse proxy on top of 3 static nginx servers,
used to demonstrate the important concepts of `double_advanced` without getting bogged down in complexities