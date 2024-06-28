<div class="tabs">
  <input type="radio" id="tab1" name="tab-control" checked>
  <input type="radio" id="tab2" name="tab-control">
  <input type="radio" id="tab3" name="tab-control">
  
  <ul>
    <li title="Tab 1"><label for="tab1" role="button"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M464 48H48C21.49 48 0 69.49 0 96v320c0 26.51 21.49 48 48 48h416c26.51 0 48-21.49 48-48V96c0-26.51-21.49-48-48-48zm-16 272H352V160h96zm-128 0H224V160h96zm-128 0H96V160h96zM96 208h96v112H96zm128 112v-112h96v112zm128 0v-112h96v112z"/></svg></label></li>
    <li title="Tab 2"><label for="tab2" role="button"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M464 48H48C21.49 48 0 69.49 0 96v320c0 26.51 21.49 48 48 48h416c26.51 0 48-21.49 48-48V96c0-26.51-21.49-48-48-48zm-16 272H352V160h96zm-128 0H224V160h96zm-128 0H96V160h96zM96 208h96v112H96zm128 112v-112h96v112zm128 0v-112h96v112z"/></svg></label></li>
    <li title="Tab 3"><label for="tab3" role="button"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M464 48H48C21.49 48 0 69.49 0 96v320c0 26.51 21.49 48 48 48h416c26.51 0 48-21.49 48-48V96c0-26.51-21.49-48-48-48zm-16 272H352V160h96zm-128 0H224V160h96zm-128 0H96V160h96zM96 208h96v112H96zm128 112v-112h96v112zm128 0v-112h96v112z"/></svg></label></li>
  </ul>
  
  <div class="slider">
    <div class="indicator"></div>
  </div>
  
  <div class="content">
    <section>
      <h2>Tab 1 Content</h2>
      <p>This is the content of Tab 1.</p>
    </section>
    <section>
      <h2>Tab 2 Content</h2>
      <p>This is the content of Tab 2.</p>
    </section>
    <section>
      <h2>Tab 3 Content</h2>
      <p>This is the content of Tab 3.</p>
    </section>
  </div>
</div>

<style>
.tabs {
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.tabs ul {
  display: flex;
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.tabs ul li {
  flex: 1;
  text-align: center;
  cursor: pointer;
  position: relative;
  transition: background-color 0.3s ease;
}

.tabs ul li:hover {
  background-color: #f0f0f0;
}

.tabs ul li label {
  display: block;
  padding: 15px 0;
  color: #333;
  font-weight: bold;
  text-transform: uppercase;
  transition: color 0.3s ease;
}

.tabs ul li input[type="radio"] {
  display: none;
}

.tabs ul li input[type="radio"]:checked + label {
  color: #007bff;
}

.slider {
  height: 3px;
  background-color: #007bff;
  position: relative;
}

.indicator {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 33.333%;
  background-color: #007bff;
  transition: transform 0.3s ease;
}

.content {
  padding: 20px 0;
}

.content section {
  display: none;
}

.content section:first-child {
  display: block;
}

input[type="radio"]:checked ~ .slider .indicator {
  transform: translateX(100%);
}

input[type="radio"]:checked ~ .content section {
  display: none;
}

input[type="radio"]:checked ~ .content section:nth-child(1),
input[type="radio"]:checked ~ .tabs ul li:nth-child(1) {
  display: block;
}

input[type="radio"]:checked ~ .content section:nth-child(2),
input[type="radio"]:checked ~ .tabs ul li:nth-child(2) {
  display: block;
}

input[type="radio"]:checked ~ .content section:nth-child(3),
input[type="radio"]:checked ~ .tabs ul li:nth-child(3) {
  display: block;
}
</style>
