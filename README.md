<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ekin's Cooking Guide</title>

  <style>
    /* ===== COLOR THEME ===== */
    :root {
      --baby-green: #cfe8dc;
      --beige: #f6f3ea;
      --dark-green: #5f8f7e;
      --white: #ffffff;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: var(--beige);
      display: flex;
      height: 100vh;
      overflow: hidden;
      color: #333;
    }

    /* ===== LEFT CONTENT ===== */
    .left {
      width: 65%;
      padding: 60px;
      animation: fadeIn 1.5s ease;
    }

    h1 {
      font-size: 3rem;
      color: var(--dark-green);
      margin-bottom: 10px;
    }

    h2 {
      margin-top: 40px;
      color: var(--dark-green);
    }

    p {
      max-width: 600px;
      line-height: 1.6;
    }

    .editable-box {
      background: var(--white);
      padding: 20px;
      border-left: 6px solid var(--baby-green);
      border-radius: 8px;
      margin-top: 25px;
    }

    /* ===== RIGHT IMAGE SCROLLER ===== */
    .right {
      width: 35%;
