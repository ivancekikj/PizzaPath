<h1>PizzaPath</h1>

<p>
  A modular web application for managing orders and customers in a small pizzeria.
  Features an automatically generated admin panel for managing content (menu, order,
  accounts, newsletter), a reactive easy-to-use user interface for customer interaction and
  an email sending functionality (email confirmation, promotions). Uses a hybrid
  architecture with a monolith (Svelte, Django) and additional microservices (FastApi).
  Utilizes CI/CD pipelines (linter checks, formatter checks and containerization), a reverse
  proxy for simplified access and container orchestration to run the entire system
  architecture.
</p>

<h2>Functionalities</h2>

<h3>Foods</h3>
<ol>
  <li>The system shall allow administrators to create, edit and delete food information.</li>
  <li>The system shall allow customers to rate previously ordered foods from 1 to 5.</li>
</ol>

<h3>Orders</h3>
<ol>
  <li>The system shall allow customers to create orders.</li>
  <li>The system shall allow the customer one order at a time.</li>
  <li>The system shall allow the customer to add foods to their order.</li>
  <li>The system shall allow the customer to customize their chosen food.</li>
  <li>The system shall allow administrators to update the order status.</li>
  <li>The system shall allow customers to view the latest order status.</li>
  <li>The system shall keep track of order history.</li>
</ol>

<h3>Newsletter</h3>
<ol>
  <li>The system shall allow customers to subscribe to a newsletter.</li>
  <li>The system shall allow administrators to post content on the newsletter.</li>
  <li>The system shall email new newsletter content to subscribed customers.</li>
</ol>

<h3>Static information</h3>
<ol>
  <li>The system shall display static information about the company to customers.</li>
</ol>

<h3>Customer rewards</h3>
<ol>
  <li>The system shall reward the customer coupons for each order.</li>
  <li>The system shall allow the user to redeem their coupons for free food.</li>
</ol>

<h3>Accounts</h3>
<ol>
  <li>The system shall require customers to confirm their email.</li>
  <li>The system shall allow a super administrator to add and remove administrators.</li>
  <li>The system shall allow customers to edit their personal information.</li>
</ol>


<h2>Architecture</h2>

<h2>Pages</h2>

<h2>Repositories</h2>

<p><a href="https://github.com/ivancekikj/PizzaPath-CustomerApp/">Customer App</a></p>
<p><a href="https://github.com/ivancekikj/PizzaPath-AdminApp/">Admin App</a></p>
<p><a href="https://github.com/ivancekikj/PizzaPath-EmailApp/">Email App</a></p>
