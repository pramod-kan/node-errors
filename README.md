# node-errors

1)SyntaxError: Unexpected token / in C:\Users\sharm\Desktop\backend\passport-auth-node\views\register.ejs while compiling ejs
solution:- didnt created folder 'partial'   <% include ../partials/header %> 

2)Express.js req.body undefined
solution:-express.bodyParser() is no longer bundled as part of express. You need to install it separately before loading:
