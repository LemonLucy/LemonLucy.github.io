---
widget: slider

headless: true

weight: 10

title: ''

type: landing

block: slider
content:
    slides:
    - title: "Smart Farm"
        content: "Development of apps related to smart farming"
        align: center
        background:
            image:
                filename: smartfarm.jpg
                filters:
                    brightness: 0.4
            position: center
            color: '#000'

    - title: "Cloud Computing"
        content: "Cloud Computing with AWS"
        align: center
        background:
            image:
                filename: aws.jpg
                filters:
                    brightness: 0.4
            position: center
            color: '#000'

    - title: "Mathematics"
        content: "Mathematics related to AI"
        align: center
        background:
            image:
                filename: mathematics.jpg
                filters:
                    brightness: 0.4
            position: center
            color: '#000'

    - title: "Development"
        content: "Full-Stack application development"
        align: center
        background:
            image:
                filename: development.jpg
                filters:
                    brightness: 0.4
            position: center
            color: '#000'


design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    slide_height: '350px'
    is_fullscreen: true
    # Automatically transition through slides?
    loop: true
    # Duration of transition between slides (in ms)
    interval: 3000

---
