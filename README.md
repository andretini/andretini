
<div class="tabs" style="max-width: 600px; margin: 0 auto; padding: 20px; box-shadow: 0 0 10px rgba(0,0,0,0.1);">
  <input type="radio" id="tab1" name="tab-control" checked>
  <input type="radio" id="tab2" name="tab-control">
  <input type="radio" id="tab3" name="tab-control">
  
  <ul style="display: flex; list-style-type: none; margin: 0; padding: 0;">
    <li style="flex: 1; text-align: center; cursor: pointer; position: relative; transition: background-color 0.3s ease;" title="Tab 1">
      <label for="tab1" role="button" style="display: block; padding: 15px 0; color: #333; font-weight: bold; text-transform: uppercase; transition: color 0.3s ease;">Tab 1</label>
    </li>
    <li style="flex: 1; text-align: center; cursor: pointer; position: relative; transition: background-color 0.3s ease;" title="Tab 2">
      <label for="tab2" role="button" style="display: block; padding: 15px 0; color: #333; font-weight: bold; text-transform: uppercase; transition: color 0.3s ease;">Tab 2</label>
    </li>
    <li style="flex: 1; text-align: center; cursor: pointer; position: relative; transition: background-color 0.3s ease;" title="Tab 3">
      <label for="tab3" role="button" style="display: block; padding: 15px 0; color: #333; font-weight: bold; text-transform: uppercase; transition: color 0.3s ease;">Tab 3</label>
    </li>
  </ul>
  
  <div class="slider" style="height: 3px; background-color: #007bff; position: relative;">
    <div class="indicator" style="position: absolute; top: 0; left: 0; height: 100%; width: 33.333%; background-color: #007bff; transition: transform 0.3s ease;"></div>
  </div>
  
  <div class="content" style="padding: 20px 0;">
    <section style="display: block;">
      <h2>Tab 1 Content</h2>
      <p>This is the content of Tab 1.</p>
    </section>
    <section style="display: none;">
      <h2>Tab 2 Content</h2>
      <p>This is the content of Tab 2.</p>
    </section>
    <section style="display: none;">
      <h2>Tab 3 Content</h2>
      <p>This is the content of Tab 3.</p>
    </section>
  </div>
</div>
