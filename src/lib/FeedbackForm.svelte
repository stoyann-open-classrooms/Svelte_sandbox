<script>
import Button from "./Button.svelte";

let text = ''

let btnDisabled = true

</script>

<form>
    <!-- Rating select -->
    <div class="input-group">
        <input type="text" placeholder="Tell us something that keeps you coming back">
    <Button disabled={btnDisabled} type='submit' >Send</Button>
    </div>
</form>



<style>
    header {
      max-width: 400px;
      margin: auto;
    }
  
    header h2 {
      font-size: 22px;
      font-weight: 600;
      text-align: center;
    }
  
    .input-group {
      display: flex;
      flex-direction: row;
      border: 1px solid #ccc;
      padding: 8px 10px;
      border-radius: 8px;
      margin-top: 15px;
    }
  
    input {
      flex-grow: 2;
      border: none;
      font-size: 16px;
    }
  
    input:focus {
      outline: none;
    }
  
    .message{
      padding-top: 10px;
      text-align: center;
      color: rebeccapurple;
    }
  </style>