Now you have made navbar. So, let's build the home page.

1. Create a div tag and add the class name `home` to it.

   In this div element we will write our home page content.

   ```html
    <div class="home"></div>
   ```

2. Add a paragraph tag `p` in that div element. Then write `Recent Misson` in it.

   ```html
    <div class="home">
        <p>Recent misson</p>
    </div>
   ```

3. Add a `h2` tag in div element. Then write `Crew-5 misson` in it.

   ```html
    <div class="home">
        <p>Recent misson</p>
        <h1>Crew-5 misson</h1>
    </div>
   ```

4. At last create a button tag in the div element. Then write `Rewatch` in it.

   ```html
    <div class="home">
        <p>Recent misson</p>
        <h1>Crew-5 misson</h1>
        <button>Rewatch</button>
    </div>
   ```

3. Set the display to flex and flex-direction to `column` to the div element.

   ```css
   .home {
    display: flex;
    flex-direction: column;
   }
   ```

4. Make sure that the all tag in div element should be in right and little in bottom as you see in the image.