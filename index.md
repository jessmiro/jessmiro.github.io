your valentines
---

<form>
  <input id="userID" maxlength="3">
  <input onclick="return findProject()" type="submit" value="Go">
</form>

<script>
  function findProject(){
    if (document.getElementById('userId').value = 'hi'){
      location.href = '/resources.html';
    }
    else {
    location.href = 'about-me.html';
    }
    // document.location = '/' + document.getElementById('userId').value();
  }
</script>
