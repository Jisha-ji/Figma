# Ex09 Event Registration Web Application
# Date:25.11.2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
``` 
page 1

<style>
.auth-container {
  border-radius: 50px;
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  font-size: 20px;
  font-weight: 400;
  margin: 0 auto;
}

.auth-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 806px;
  width: 100%;
  align-items: center;
  padding: 17px 18px 383px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.header-logo {
  aspect-ratio: 6.67;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.main-logo {
  aspect-ratio: 1.01;
  object-fit: contain;
  object-position: center;
  width: 189px;
  margin-top: 10px;
  max-width: 100%;
}

.login-text {
  position: relative;
  color: #f1e9e9;
  text-shadow: 0px 8px 12px rgba(0, 0, 0, 0.15), 0px 4px 4px rgba(0, 0, 0, 0.3);
  font-family: Inter, sans-serif;
  mix-blend-mode: color-dodge;
  z-index: 10;
  margin: -22px 0 0 13px;
}

.konkhmer-font {
  font-family: Konkhmer Sleokchher, -apple-system, Roboto, Helvetica, sans-serif;
}

.white-text {
  color: rgba(241, 233, 233, 1);
}

.register-button {
  position: relative;
  background-color: rgba(27, 25, 25, 1);
  box-shadow: 0px 16px 32px -8px rgba(12, 12, 13, 0.4);
  width: 160px;
  max-width: 100%;
  font-family: Konkhmer Sleokchher, -apple-system, Roboto, Helvetica, sans-serif;
  color: rgba(255, 255, 255, 1);
  margin: 33px 0 -77px;
  padding: 1px 1px 19px;
  cursor: pointer;
  border: none;
  text-align: center;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="auth-container">
  <div class="auth-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/8fe86bf807f6bd385b6c54b005cc13a132953f0277a8dbd5a9b4e7c55df8584c?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/2623e290f3469bf1fa8ffe6c6df7410c51f5828d7db2dcedc8e93a3d976c7f75?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
      class="header-logo"
      alt="Header Logo"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/a35e954bf1fc153fbd78134c0645746a1365f7bd305db2d3b6f06f7bd4d665d0?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
      class="main-logo"
      alt="Main Logo"
    />
    <div class="login-text">
      <br />
      <br />
      <span class="konkhmer-font">L</span>
      <span class="konkhmer-font white-text">LOGIN</span>
    </div>
    <button class="register-button" tabindex="0">REGISTER</button>
  </div>
</div>

page 2

<style>
.sports-events-container {
  border-radius: 20px;
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  font: 400 20px Irish Grover, sans-serif;
}

.events-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 806px;
  width: 100%;
  align-items: start;
  padding: 58px 20px 342px 49px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.events-title {
  position: relative;
  color: #000;
  text-shadow: 0px 8px 12px rgba(0, 0, 0, 0.15), 0px 4px 4px rgba(0, 0, 0, 0.3);
  align-self: end;
  font: 600 24px Inknut Antiqua, sans-serif;
}

.event-item {
  position: relative;
  display: flex;
  gap: 15px;
  margin: 30px 0 0 26px;
  align-items: center;
}

.event-item:first-of-type {
  margin-top: 14px;
  margin-left: 29px;
}

.event-icon {
  aspect-ratio: 1.25;
  object-fit: contain;
  object-position: center;
  width: 15px;
}

.cricket-icon {
  background-color: #1f1d1d;
  width: 15px;
  height: 12px;
  margin-top: 6px;
}

.event-name {
  font: 400 20px Irish Grover, sans-serif;
  color: #000;
}

.decorative-image {
  aspect-ratio: 0.83;
  object-fit: contain;
  object-position: center;
  width: 5px;
  margin: 6px 0 0 44px;
}

.decorative-image-round {
  aspect-ratio: 1;
  width: 6px;
  margin: 11px 0 0 43px;
}

.decorative-image-rect {
  aspect-ratio: 1.67;
  width: 10px;
  border-radius: 3px;
}

.decorative-image-small {
  aspect-ratio: 1.33;
  width: 8px;
  margin: 25px 0 -68px 41px;
}
</style>

<div class="sports-events-container">
  <div class="events-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/9dba4aa43736f26954b0f3441f474a2985a89f626604466ab16243aeb8d07070?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
      class="background-image"
      alt=""
    />
    <h1 class="events-title">SPORTS DAY EVENTS</h1>
    
    <div class="event-item">
      <div class="cricket-icon" role="img" aria-label="Cricket icon"></div>
      <span class="event-name">Cricket</span>
    </div>

    <div class="event-item">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/926e34d908f4e2ec1582370cb81802a86adac00018cdf3928b0bd36f3a889728?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
        class="event-icon"
        alt="Badminton icon"
      />
      <span class="event-name">Badminton</span>
    </div>

    <div class="event-item">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/1a9b7ef4f13c8e38ec46cfe613cd642d60e0abbfeba14a77a154eb73ab95ca4c?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
        class="event-icon"
        alt="Volleyball icon"
      />
      <span class="event-name">Volley Ball</span>
    </div>

    <div class="event-item">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/76c9548d3b239667c7f6efaa4cd34502fabbe25e564d3f7f6975338ff066ad01?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
        class="event-icon"
        alt="Running icon"
      />
      <span class="event-name">100 mts</span>
    </div>

    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/8c41c4f31b54224b429b591e281db87ca7dcb8b5a84108cb078507f7e6b364e2?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
      class="decorative-image"
      alt=""
    />

    <div class="event-item">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/18f22d2725e020ff4682a50ccd37fcc5d6eab0571394b373889e8f01850a904b?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
        class="event-icon"
        alt="Relay race icon"
      />
      <span class="event-name">4*100 Relay</span>
    </div>

    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/6bd7e6e2c5455060f17e4c70d190d2cf5b2bb25dfe3757aba69b5dd6a2530c7c?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
      class="decorative-image-round"
      alt=""
    />

    <div class="event-item">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/527f6c32d9767101dfa04f5e0bebb4780363f77b8450c1618d579b464f140ecf?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
        class="event-icon"
        alt="Track icon"
      />
      <span class="event-name">400 mts</span>
    </div>

    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/a825382ae98baf4b0493455f48f587f0c4f6c33dc7f5020f23b1a69bbe3ab142?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
      class="decorative-image-rect"
      alt=""
    />

    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/03b6e8348d1344cdb00f265b93b47194fcced9dbafa486d033b66044cfc31358?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
      class="decorative-image-small"
      alt=""
    />
  </div>
</div>

page 3

<style>
.registration-container {
  border-radius: 20px;
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  font: 400 21px Magra, sans-serif;
}

.registration-wrapper {
  display: flex;
  flex-direction: column;
  border-radius: 28px;
  position: relative;
  min-height: 806px;
  width: 100%;
  align-items: start;
  padding: 141px 40px 141px 80px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.form-title {
  position: relative;
  color: #f82121;
  text-shadow: 0px 8px 12px rgba(0, 0, 0, 0.15), 0px 4px 4px rgba(0, 0, 0, 0.3);
  font-family: Maitree, sans-serif;
  font-weight: 500;
}

.input-field {
  position: relative;
  background-color: #d9d9d9;
  width: 230px;
  max-width: 100%;
  padding: 4px 0 20px;
  margin-top: 20px;
}

.magra-text {
  font-family: Magra, sans-serif;
  font-weight: 400;
}

.monofett-text {
  font-family: Monofett, sans-serif;
  font-size: 36px;
}

.register-button {
  position: relative;
  align-self: center;
  z-index: 10;
  margin-top: 11px;
  border: none;
  background: transparent;
  cursor: pointer;
}

.button-background {
  position: relative;
  border: 1px solid var(--Miscellaneous-Button---Tinted-Fill, rgba(0, 122, 255, 0.15));
  background: var(--Miscellaneous-Button---Disabeld-BG, rgba(118, 118, 128, 0.12));
  box-shadow: 0px 8px 12px 6px rgba(0, 0, 0, 0.15), 0px 4px 4px 0px rgba(0, 0, 0, 0.3);
  width: 181px;
  height: 51px;
  margin: 0 0 -30px 30px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="registration-container">
  <div class="registration-wrapper">
    <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/16b70c205c255a296cfb1a3b58d408b56f6e0edaf86f3bfd5ce2f17076d90eee?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3" alt="" class="background-image" />
    
    <form>
      <h1 class="form-title">EVENT REGISTRATION FORM</h1>
      
      <div class="input-field">
        <label for="fullName" class="visually-hidden">Full Name</label>
        <input type="text" id="fullName" class="magra-text" aria-label="Full Name" required />
      </div>

      <div class="input-field">
        <label for="gender" class="visually-hidden">Gender</label>
        <select id="gender" aria-label="Gender" required>
          <option value="">Select Gender</option>
          <option value="male">Male</option>
          <option value="female">Female</option>
          <option value="other">Other</option>
        </select>
      </div>

      <div class="input-field">
        <label for="age" class="visually-hidden">Age</label>
        <input type="number" id="age" aria-label="Age" required />
      </div>

      <div class="input-field">
        <label for="registerNumber" class="visually-hidden">Register Number</label>
        <input type="text" id="registerNumber" aria-label="Register Number" required />
      </div>

      <div class="input-field">
        <label for="department" class="visually-hidden">Department</label>
        <input type="text" id="department" aria-label="Department" required />
      </div>

      <div class="input-field">
        <label for="mobileNumber" class="visually-hidden">Mobile Number</label>
        <input type="tel" id="mobileNumber" aria-label="Mobile Number" required />
      </div>

      <div class="input-field">
        <label for="events" class="visually-hidden">Events to Register</label>
        <select id="events" aria-label="Events to Register" required>
          <option value="">Select Events</option>
        </select>
      </div>

      <button type="submit" class="register-button">
        <span class="monofett-text">REGISTER</span>
      </button>
      <div class="button-background"></div>
    </form>
  </div>
</div>

page 4

<style>
.thank-you-container {
  border-radius: 20px;
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  font-family: Marko One, sans-serif;
  font-weight: 400;
  margin: 0 auto;
}

.content-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 806px;
  width: 100%;
  padding: 14px 0 71px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.header-section {
  position: relative;
  display: flex;
  width: 100%;
  padding-left: 14px;
  flex-direction: column;
}

.logo {
  aspect-ratio: 6.67;
  object-fit: contain;
  object-position: center;
  width: 446px;
}

.main-title {
  color: rgba(25, 23, 23, 1);
  font-size: 48px;
  align-self: center;
  margin-top: 72px;
}

.divider {
  background-color: rgba(217, 217, 217, 1);
  width: 1px;
  height: 8px;
  margin: 60px 0 0 78px;
}

.subtitle {
  color: rgba(25, 24, 24, 1);
  font-size: 20px;
  align-self: center;
}

.contact-info {
  position: relative;
  color: rgba(0, 0, 0, 1);
  font-size: 20px;
  align-self: start;
  margin-top: 321px;
  font-family: Marcellus, sans-serif;
}
</style>

<div class="thank-you-container">
  <div class="content-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/39ceab0a7ded42b988b663d96e29943ba4b4bba59dfda2136101ce4a1700500c?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
      class="background-image"
      alt="Background decoration"
    />
    <div class="header-section">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/71064c7fd033f2f83eeb7a2447bf42b87260660e47f7bbf0ff0e3be8182ff943?placeholderIfAbsent=true&apiKey=db81f61e7afa487ba91cf38f2fab93f3"
        class="logo"
        alt="Company logo"
      />
      <h1 class="main-title">THANK YOU</h1>
      <div class="divider"></div>
      <p class="subtitle">WE ARE EAGERLY WAITING FOR YOUR PARTICIPATION</p>
    </div>
    <div class="contact-info">
      CONTACT US:<br /><br />
      Email - Saveethaengineeringcollege@gmail.com<br /><br />
      phone - 6369183394
    </div>
  </div>
</div>
```
# OUTPUT:
![alt text](<Screenshot (128).png>)
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
