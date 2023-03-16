<template>
  <div class="contact">
    <h3>Out contact information</h3>
    <ul>
      <li>
        <span>Country:</span>  Philippines
      </li>
      <li>
          <span>City:</span>  Bonifacio Global City Taguig City 1634, 
        </li>
      <li>
          <span>Address:</span>  12th Floor The Trade & Financial Tower U1206 7th Ave. & 32nd St.
      </li>
      <li>
          <span>Phone:</span>  <a href="tel:+359878855868">+359878855868</a>
      </li>
      <li>
          <span>E-mail:</span>  <a href="mailto:office@buycardsfor.games">office@buycardsfor.games</a>
      </li>
    </ul>
    <h3>Company details</h3>
    <ul>
        <li>
          <span>Company:</span>  Games Haven GmbH
        </li>
        <li>
            <span>VAT #:</span>  454 671 887 12
          </li>
      </ul>
  </div>
</template>

<script>
export default {
  name: 'contact',
}
</script>


<style lang="scss">
.contact h3 {
  margin-top:15px; 
  margin-bottom: 15px;
}

.contact ul {
  padding-left: 20px;
}

.contact ul li {
  margin-top:10px;
}

.contact ul li span {
  text-transform: uppercase;
  text-decoration:underline;
  color:rgb(206, 240, 106);
}

.contact a {
  color:rgb(26, 231, 224);
  text-decoration:none;
}
</style>


