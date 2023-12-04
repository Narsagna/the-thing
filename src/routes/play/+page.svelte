<div class="mainContainer">
  <div
    class="stats w-2/5 min-w-fit stats-horizontal lg:stats-horizontal shadow bg-hyperswitch-bg text-white"
  >
    <div class="stat">
      <div class="stat-title">Orders</div>
      <div class="stat-value">31K</div>
    </div>

    <div class="stat">
      <div class="stat-title">Success Rate</div>
      <div class="stat-value">60%</div>
    </div>

    <div class="stat">
      <div class="stat-title">Days Left</div>
      <div class="stat-value">90</div>
    </div>
  </div>

  <div class="chatContainer w-2/5 min-w-fit flex flex-col">
    <div class="chat chat-start">
      <div class="chat-bubble bg-hyperswitch-blue text-white">
        That's never been done in Jedi history. It's insulting!
      </div>
    </div>
    <div class="chat chat-end">
      <div class="chat-bubble chat-bubble-info bg-hyperswitch-blue text-white">
        Calm down, Anakin.
      </div>
    </div>
  </div>

  <button class="btn btn-outlin btn-info">User Action</button>

  <div class="card w-2/5 min-w-fit bg-hyperswitch-bg shadow-xl text-white">
    <div class="card-body">
      <h2 class="card-title">Graph</h2>
    </div>
  </div>

  <div class="overflow-x-auto text-white w-2/5 min-w-fit">
    <table class="table">
      <!-- head -->

      <tbody>
        <!-- row 1 -->
        <tr>
          <td>Connectors</td>
          <td class="text-center">
            <button class="btn btn-sm bg-hyperswitch-blue text-white w-full"
              >Add</button
            >
          </td>
          <td class="text-center"
            ><button class="btn btn-sm bg-hyperswitch-blue text-white w-full"
              >Remove</button
            >
          </td>
        </tr>
        <!-- row 2 -->
        <tr>
          <td>Payment Routing</td>
          <td class="text-center">
            <button class="btn btn-sm bg-hyperswitch-blue text-white w-full"
              >Cost Based</button
            >
          </td>
          <td class="text-center">
            <button class="btn btn-sm bg-hyperswitch-blue text-white w-full"
              >Volume Based</button
            >
          </td>
        </tr>
        <!-- row 3 -->
        <tr>
          <td>Payment Experience</td>
          <td class="text-center">
            <button class="btn btn-sm bg-hyperswitch-blue text-white w-full"
              >Embedded</button
            >
          </td>
          <td class="text-center">
            <button class="btn btn-sm bg-hyperswitch-blue text-white w-full"
              >Redirect</button
            >
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<style>
  .card {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .mainContainer {
    min-height: 100vh;
    background-color: black;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    flex: 1;
    padding: 24px;
    gap: 10px;
  }

  .mainContainer button {
    background-color: #016df9;
    color: white;
  }

  .mainContainer button:hover {
    opacity: 0.7;
  }
</style>
