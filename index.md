your valentines
---

<form>
  <input id="userID" maxlength="3">
  <input onclick="return findProject()" type="submit" value="Go">
</form>

<script>
  function findProject(){
    if (document.getElementById('userId').value() = '111'){
      location.href = '/resources.html';
    }
    else
    location.href = 'index.html';
    // document.location = '/' + document.getElementById('userId').value();
  }
</script>
