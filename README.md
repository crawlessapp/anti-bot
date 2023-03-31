

# Crawless Browser Fingerprint Solution

## Intro

At Crawless Labs we made our own `Browser Fingerprint` solution which can generate unlimited amount of unique fingerprints by changing all possible browser properties.

There is a list of all supported features:
  - `canvas`
  - `audio`
  - `webgl`
  - `webrtc`
  - `fonts`
  - `navigator`
  - `window`
  - `screen`
  - `eval`
  - `webdriver`
  - `performance`
  - `outerdimensions`
  - `speech`
  - `permissions`
  - `user-agent data`
  - `iframe`
  - `date`
  - `timezone`
  - `rtt`

We can emulate Chrome and Brave browsers with confidence which is almost impossible to detect.

It is well tested and covers all possible anti-bot websites.
It can bypass: `Cloudflare`, `DistillNetwork`, `Akamai`, `Datadome`, `PerimeterX`, `reCaptcha v3`, etc.



## Examples

### [fingerprint.com](https://fingerprint.com/demo/)

Each time we run we can generate new fingerprint id here.

<img src="https://user-images.githubusercontent.com/88615762/229175617-7bb71de6-34b8-402e-9778-95fceac53972.png" alt="fingerprint.com bypass" title="fingerprint.com bypass" width="750" height="450" />
 

### [creepjs](https://abrahamjuliot.github.io/creepjs)

Here we have 2 different fingerprints. CreepJS does a good job on checking all possible lower and higher entropy values but not for us.

[<img src="https://user-images.githubusercontent.com/88615762/229144006-1920b8e1-4ca8-4480-ad72-3831802b9c9b.jpg" alt="creepjs 1" title="creepjs fingerprint 1" width="150" height="900" />](https://user-images.githubusercontent.com/88615762/229144006-1920b8e1-4ca8-4480-ad72-3831802b9c9b.jpg)
[<img src="https://user-images.githubusercontent.com/88615762/229145151-32663a26-3d75-4a0a-9b68-1f58db07f56d.jpg" alt="creepjs 2" title="creepjs fingerprint 2" width="150" height="900" />](https://user-images.githubusercontent.com/88615762/229145151-32663a26-3d75-4a0a-9b68-1f58db07f56d.jpg)


### [Browser Leaks](https://browserleaks.com)

**Canvas test**

[>>> Watch Video <<<](https://youtu.be/PWgiTaTWyBA)

[<img src="https://user-images.githubusercontent.com/88615762/229146918-749a6096-0cb4-4810-b038-767c18b3cb4f.png" alt="browserleaks 1" title="browserleaks fingerprint 1" width="750" height="450" />](https://youtu.be/PWgiTaTWyBA)

[<img src="https://user-images.githubusercontent.com/88615762/229146929-db506f7c-a520-48ad-a1fe-a89b515f7d93.png" alt="browserleaks 2" title="browserleaks fingerprint 2" width="750" height="450" />](https://youtu.be/PWgiTaTWyBA)


**Fonts test**

[>>> Watch Video <<<](https://youtu.be/-aiwvfajupA)

[<img width="750" height="450" alt="Fonts Fingerprint" src="https://user-images.githubusercontent.com/88615762/229154080-92247510-0658-4a0e-8a78-fde6047f4b08.png">](https://youtu.be/-aiwvfajupA)


### [Cloudflare bypass](https://www.cloudflare.com)

Test was made on [https://nowsecure.nl](https://nowsecure.nl)

[>>> Watch Video <<<](https://youtu.be/HqsHILruzG4)

[<img width="750" height="450" alt="Cloudflare bypass" src="https://user-images.githubusercontent.com/88615762/229161090-55be684e-8034-45e1-b43e-043311490e16.png">](https://youtu.be/HqsHILruzG4)

[<img width="750" height="450" alt="Cloudflare bypass" src="https://user-images.githubusercontent.com/88615762/229162001-d013e502-630f-463c-9d85-0864280bc6b1.png">](https://youtu.be/HqsHILruzG4)

### [Wizz Air](https://wizzair.com)

On WizzAir the Akamai anti-bot is used with high level of protection.

[>>> Watch Video <<<](https://youtu.be/Nc5VclUpKIM)

[<img width="750" height="450" alt="WizzAir without fingerprint" src="https://user-images.githubusercontent.com/88615762/229157675-6dd5fb47-b3c8-4076-8472-402f547e666d.png">](https://youtu.be/Nc5VclUpKIM)

[<img width="750" height="450" alt="WizzAir with fingerprint" src="https://user-images.githubusercontent.com/88615762/229157664-a6e740c8-c12d-4eeb-9939-653ef729ca0b.png">](https://youtu.be/Nc5VclUpKIM)


### [Akamai](https://www.akamai.com)

Demo on how easy it is to generate `sensor_data` for Akamai. You can use it as sensor_data generator on any website which have akamai protection

[>>> Watch Video <<<](https://youtu.be/kKnlb8fee8U)

[<img width="750" height="450" alt="Akamai sensor_data generator" src="https://user-images.githubusercontent.com/88615762/229172713-3d8a2579-0904-47a7-9908-2565306d982f.png">](https://youtu.be/kKnlb8fee8U)
