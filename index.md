your valentines
---

<form>
  <input id="userID" maxlength="3">
  <input onclick="return findProject()" type="submit" value="Go">
</form>

<script>
  function findProject(){
    if (document.getElementById('userId').value() = '111'){
      document.location = '/daniela.html';
    }
    else
    document.location = 'index.html';
    // document.location = '/' + document.getElementById('userId').value();
  }
</script>
