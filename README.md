# final_project

I am using dream.ischool.berkeley.edu at the moment.

Please follow the below steps to render content as you would see in https://dream.ischool.berkeley.edu/~kakkineni/w209

1. copy the images to your images directory. I have my images here (/home/kakkineni/w209/static/images)

2. copy the dollarsVsdeaths.html into your templates directory. I have my templates here (/home/kakkineni/w209/templates)

3. copy the style.css into your styles directory. I have my styles here (/home/kakkineni/w209/static/styles)

4. copy the video.js (not using at the moment - but referenced in the code) into your js directory. I have my js here (/home/kakkineni/w209/static/js)

5. MAKE SURE THAT YOU HAVE YOUR PATHS CORRECT in dollarsVsdeaths.html file. 

like in line-8 line-42 , line-51 for now.

6. One last step is that you need to edit your w209.py in your home directory and change the default one you have to below:

@app.route("/")
def w209():
    return render_template("dollarsVsdeaths.html")

7. Now do touch start.wsgi and you should be see the output here

https://dream.ischool.berkeley.edu/~<<user_name>>/w209
