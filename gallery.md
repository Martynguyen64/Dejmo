<style>
  .search-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    padding: 20px;
  }
  .search-input {
    width: 300px;
    height: 50px;
    border: none;
    border-radius: 25px;
    padding: 0 20px;
    font-size: 20px;
    margin-right: 20px;
  }
  .search-button {
    width: 150px;
    height: 50px;
    background-color: #46cee3;
    color: white;
    border: none;
    border-radius: 25px;
    font-size: 20px;
    cursor: pointer;
  }
</style>

<div class="search-container">
  <form>
    <label for="currentWeight">Current weight:</label>
    <input type="text" name="currentWeight" class="search-input" placeholder="Enter your current weight">
    <br>
    <br>
    <label for="goalWeight">Goal weight:</label>
    <input type="text" name="goalWeight" class="search-input" placeholder="Enter your goal weight">
    <br>
    <br>
    <button type="submit" class="search-button">Submit</button>
  </form>
</div>