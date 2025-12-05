<!DOCTYPE html>
<html>
<head>
    <!-- Internal CSS styling -->
    <style>
        /* Page background color */
        body {
            background: #425f7c;
        }

        /* Title (Facebook text) color */
   #title {
            color: #098be1;
   }
        /* Box container for login form */
        .login-box {
            background: white;          /* White background for form */
            padding: 40px;              /* Space inside box */
            margin: 100px auto;         /* Center alignment */
            width: 300px;               /* Box width */
            border-radius: 8px;         /* Rounded corners */
        }

        /* Styling input fields */
   input {
            width: 100%;               /* Full width */
            padding: 10px;             /* Inner spacing */
            margin: 10px 0;            /* Gap between inputs */
        }
        /* Styling login button */
        button {
            width: 100%;
            padding: 10px;
            background: #3498db;       /* Button color */
            color: white;              /* Text color */
            border: none;              /* No border */
            cursor: pointer;           /* Pointer cursor */
        }
  </style>
    <!-- Page Title -->
  <title>Login Form</title>

</head>
<body>
    <!-- Login box wrapper -->
    <div class="login-box">
        <!-- Facebook heading -->
        <h1 id="title">Facebook</h1>
        <!-- Login subheading -->
        <h2>Login</h2>
        <!-- Login form -->
        <form>
            <!-- Username input -->
            <label>Username</label>
            <input type="text" placeholder="Enter Username">
            <!-- Password input -->
            <label>Password</label>
            <input type="password" placeholder="Enter Password">
            <!-- Login button -->
            <button type="submit">Login</button>
        </form>
    </div>

</body>
</html>
