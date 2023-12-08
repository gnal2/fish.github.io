# Welcome to the website of Grace Laryea

<div id="my-tabs">
  <ul>
    <li><a href="#tab1">Tab 1</a></li>
    <li><a href="#tab2">Tab 2</a></li>
    <li><a href="#tab3">Tab 3</a></li>
  </ul>
  <div id="tab1">
    <h2>Tab 1 Content</h2>
    <p>This is the content of tab 1.</p>
  </div>
  <div id="tab2">
    <h2>Tab 2 Content</h2>
    <p>This is the content of tab 2.</p>
  </div>
  <div id="tab3">
    <h2>Tab 3 Content</h2>
    <p>This is the content of tab 3.</p>
  </div>
</div>



#my-tabs {
  display: flex;
  flex-direction: column;
  height: 100vh;
  overflow: auto;
}

#my-tabs ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

#my-tabs ul li {
  display: inline-block;
  margin-right: 20px;
}

#my-tabs ul li a {
  text-decoration: none;
  color: #000;
  font-weight: bold;
}

#my-tabs .tab-content {
  padding: 20px;
}

