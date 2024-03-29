

# Crawless Anti-Detect Browser Automation Software

![anti-bot fingerprints generator](https://user-images.githubusercontent.com/88615762/229354081-9ce772dc-4276-4414-a0fd-1916b4f9ad30.gif)

## About 

[![Crawless on Discord](https://discordapp.com/api/guilds/1093232860401516584/widget.png?style=banner2)](https://discord.gg/8GjY95VtAB) 

We are proud to pressent how easy it is to Automate any Web flows and grow your business by accessing most protected valuable content.

At Crawless Labs, we take pride in crafting our exceptional Browser Fingerprint solution, capable of generating unlimited amount of unique browser fingerprints by altering every conceivable browser property.

Our cutting-edge technology empowers you to access valuable content from websites that employ robust protection services, such as:

- `Shape Security`
- `DataDome`
- `Distil Imperva Incapsula`
- `PerimeterX`
- `Akamai`
- `FingerprintJS`
- `FingerprintJS Pro`
- `Kasada`
- `WhiteOps`
- `ShieldSquare`
- `ThreatMetrix`
- `F5`
- `Cloudflare`
- `Arkose Labs`
- `Human Security`
- `Sift`
- `Ocule`
- `Cheq`
- `TrafficGuard`
- `Reblaze`
- `Forter Protection`
- `Meetrics Check`
- `reCAPTCHA`
- `generic fingerprinting & bot detection`

There is just a list of supported features it can change:

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
- `useragent-data`
- `iframe`
- `timezone`
- `rtt`

Confidently emulate `Chrome` and `Brave` browsers with our solution, designed to be undetectable.


## Examples and Tests

### [https://arh.antoinevastel.com/bots/areyouheadless](https://arh.antoinevastel.com/bots/areyouheadless)

<img alt="Your are not Chrome Headless" src="https://user-images.githubusercontent.com/88615762/229228948-0a2d02a7-930d-47fe-8e97-a9f0a566da47.png">

### [reCaptcha v3](https://recaptcha-demo.appspot.com/recaptcha-v3-request-scores.php)

```json
{
  "success": true,
  "hostname": "recaptcha-demo.appspot.com",
  "challenge_ts": "2023-04-01T05:59:11Z",
  "apk_package_name": null,
  "score": 0.9,
  "action": "examples/v3scores",
  "error-codes": []
}
```

<img alt="bypass reCaptcha v3" src="https://user-images.githubusercontent.com/88615762/229268518-8c0a7586-7d43-419b-83b6-e8de83628b53.png">


### [fingerprint.com](https://fingerprint.com/demo/)

Each time we run we can generate new fingerprint id here.

<img src="https://user-images.githubusercontent.com/88615762/229175617-7bb71de6-34b8-402e-9778-95fceac53972.png" alt="fingerprint.com bypass" title="fingerprint.com bypass" />
 

### [creepjs](https://abrahamjuliot.github.io/creepjs)

Here we have 2 different fingerprints. CreepJS does a good job on checking all possible lower and higher entropy values but not for us.

[<img src="https://user-images.githubusercontent.com/88615762/229144006-1920b8e1-4ca8-4480-ad72-3831802b9c9b.jpg" alt="creepjs 1" title="creepjs fingerprint 1" width="150" height="900" />](https://user-images.githubusercontent.com/88615762/229144006-1920b8e1-4ca8-4480-ad72-3831802b9c9b.jpg)
[<img src="https://user-images.githubusercontent.com/88615762/229145151-32663a26-3d75-4a0a-9b68-1f58db07f56d.jpg" alt="creepjs 2" title="creepjs fingerprint 2" width="150" height="900" />](https://user-images.githubusercontent.com/88615762/229145151-32663a26-3d75-4a0a-9b68-1f58db07f56d.jpg)


### [Browser Leaks](https://browserleaks.com)

**Canvas test**

[**>>> Watch Video <<<**](https://youtu.be/PWgiTaTWyBA)

[<img src="https://user-images.githubusercontent.com/88615762/229146918-749a6096-0cb4-4810-b038-767c18b3cb4f.png" alt="browserleaks 1" title="browserleaks fingerprint 1" />](https://youtu.be/PWgiTaTWyBA)

[<img src="https://user-images.githubusercontent.com/88615762/229146929-db506f7c-a520-48ad-a1fe-a89b515f7d93.png" alt="browserleaks 2" title="browserleaks fingerprint 2" />](https://youtu.be/PWgiTaTWyBA)


**Fonts test**

[**>>> Watch Video <<<**](https://youtu.be/-aiwvfajupA)

[<img alt="Fonts Fingerprint" src="https://user-images.githubusercontent.com/88615762/229154080-92247510-0658-4a0e-8a78-fde6047f4b08.png">](https://youtu.be/-aiwvfajupA)


### [Cloudflare bypass](https://www.cloudflare.com)

Test was made on [https://nowsecure.nl](https://nowsecure.nl)

[>>> Watch Video <<<](https://youtu.be/HqsHILruzG4)

[<img alt="Cloudflare bypass" src="https://user-images.githubusercontent.com/88615762/229161090-55be684e-8034-45e1-b43e-043311490e16.png">](https://youtu.be/HqsHILruzG4)

[<img alt="Cloudflare bypass" src="https://user-images.githubusercontent.com/88615762/229162001-d013e502-630f-463c-9d85-0864280bc6b1.png">](https://youtu.be/HqsHILruzG4)

### [PerimeterX bypass](https://www.perimeterx.com)

Bypass PerimeterX captcha on [zillow.com](https://www.zillow.com)

<img alt="perimeterx bypass before" src="https://user-images.githubusercontent.com/88615762/230376976-ed280d4c-00fd-41b4-a403-8ba868dc99aa.png">

<img alt="perimeterx bypass after" src="https://user-images.githubusercontent.com/88615762/230377004-102975c1-e8cb-4b3d-bbab-cef48aecb6db.png">

### [Akamai](https://www.akamai.com)

Demo on how easy it is to generate `sensor_data` for Akamai. You can use it as sensor_data generator on any website which have akamai protection

[**>>> Watch Video <<<**](https://youtu.be/kKnlb8fee8U)

[<img alt="Akamai sensor_data generator" src="https://user-images.githubusercontent.com/88615762/229172713-3d8a2579-0904-47a7-9908-2565306d982f.png">](https://youtu.be/kKnlb8fee8U)

### [Wizz Air](https://wizzair.com)

On WizzAir the Akamai anti-bot is used with high level of protection.

[**>>> Watch Video <<<**](https://youtu.be/Nc5VclUpKIM)

[<img alt="WizzAir without fingerprint" src="https://user-images.githubusercontent.com/88615762/229157675-6dd5fb47-b3c8-4076-8472-402f547e666d.png">](https://youtu.be/Nc5VclUpKIM)

[<img alt="WizzAir with fingerprint" src="https://user-images.githubusercontent.com/88615762/229157664-a6e740c8-c12d-4eeb-9939-653ef729ca0b.png">](https://youtu.be/Nc5VclUpKIM)
