# blogginui
This is a blog admin uidesign created with Bootstrap 4.
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-quiv="X-UA-Compatible" content="ie=edge">
    <title>Blogen Admin Area</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" href="css/style.css">
    </head>
    <body>
        <nav class="navbar navbar-expand-sm navbar-dark bg-dark p-0">
            <div class="container">
                <a href="index.html" class="navbar-brand">Blogen</a>
              <button class="navbar-toggler" data-toggle="collapse" data-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
                </button>
                 <div class="collapse navbar-collapse" id="navbarNav">
                     <ul class="navbar-nav">
                       <li class="nav-item px-2">
                         <a href="index.html" class="nav-link active">
                           Dashbord</a>
                          </li>
                         <li class="nav-item px-2">
                         <a href="posts.html" class="nav-link active">
                           Posts</a>
                          </li>
                         <li class="nav-item px-2">
                         <a href="categories.html" class="nav-link active">
                           Categories</a>
                          </li>
                         <li class="nav-item px-2">
                         <a href="users.html" class="nav-link active">
                           Users</a>
                          </li>
                         </ul>
                     
                     <ul class="navbar-nav ml-auto">
                         <li class="nav-item dropdown mr-3">
                           <a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown">
                             <i class="fa fa-user"></i> Welcome Brad
                             </a>
                             <div class="dropdown-menu">
                               <a href="profile.html" class="dropdown-item">
                                 <i class="fa fa-user-circle"></i>Profile
                                 </a>
                                 <a href="settings.html" class="dropdown-item">
                                 <i class="fa fa-gear"></i>Settings
                                 </a>
                             </div>
                         </li>
                         <li class="nav-item">
                          <a href="login.html" class="nav-link">
                             <i class="fa fa-user-items"></i>Logout
                             </a>
                           </li>
                        </ul>
                     </div>
                 </div>
            </nav>
        
        <header id="main-header" class="py-2 bg-primary text-white">
        <div class="container">
            <div class="row">
             <div class="col-md-6">
                <h1> <i class="fa fa-gear"></i> Dashboard</h1>
                </div>
            </div>
            </div>
        </header>
        
        
        <!--Acions-->
        <section id="action" class="py-4 mb-4 bg-light">
            <div class="container">
             <div class="row">
                <div class="col-md-3">
                 <a href="#" class="btn btn-primary btn-block" data-toggle="modal" 
                    data-target="#addPostModal">
                    <i class="fa fa-plus"></i> Add Post
                    </a>
                 </div>
                 <div class="col-md-3">
                     <a href="#" class="btn btn-success btn-block" data-toggle="modal" 
                    data-target="#addCategoryModal">
                    <i class="fa fa-plus"></i> Add Category
                    </a>
                 </div>
                 <div class="col-md-3">
                 <a href="#" class="btn btn-warning btn-block" data-toggle="modal" 
                    data-target="#addUserModal">
                    <i class="fa fa-plus"></i> Add User
                    </a>
                     </div>
                </div>
            </div>
        </section>
        
        
        <!--POSTS-->
        <section id="posts">
            <div class="container">
              <div class="row">
                <div class="col-md-9">
                  <div class="card">
                    <div class="card-header bg-dark text-light">
                      <h4>Latest Posts</h4>
                        </div>
                      <table class="table table-stiped">
                        <thread class="thread-inverse">
                          <tr>
                            <th>#</th>
                              <th>Title</th>
                              <th>Category</th>
                              <th>Date Posted</th>
                              <th></th>
                            </tr>
                          </thread>
                          <tbody>
                          <tr>
                              <td scope="row">1</td>
                              <td>Post One</td>
                              <td>Web Development</td>
                              <td>July 12, 2017</td>
                              <td><a href="details.html" class="btn btn-secondary"><i class="fa fa-angle-double-right"></i> Details</a></td>
                              </tr>
                              <tr>
                              <td scope="row">2</td>
                              <td>Post Two</td>
                              <td>Tech Gadgets</td>
                              <td>July 13, 2017</td>
                              <td><a href="details.html" class="btn btn-secondary"><i class="fa fa-angle-double-right"></i> Details</a></td>
                              </tr>
                              <tr>
                              <td scope="row">3</td>
                              <td>Post Three</td>
                              <td>Web Development</td>
                              <td>July 14, 2017</td>
                              <td><a href="details.html" class="btn btn-secondary"><i class="fa fa-angle-double-right"></i> Details</a></td>
                              </tr>
                              <tr>
                              <td scope="row">4</td>
                              <td>Post Four</td>
                              <td>Business</td>
                              <td>July 15, 2017</td>
                              <td><a href="details.html" class="btn btn-secondary"><i class="fa fa-angle-double-right"></i> Details</a></td>
                              </tr>
                              <tr>
                              <td scope="row">5</td>
                              <td>Post Five</td>
                              <td>Web Development</td>
                              <td>July 16, 2017</td>
                              <td><a href="details.html" class="btn btn-secondary"><i class="fa fa-angle-double-right"></i> Details</a></td>
                              </tr>
                              <tr>
                              <td scope="row">6</td>
                              <td>Post Six</td>
                              <td>Health and Wellness</td>
                              <td>July 17, 2017</td>
                              <td><a href="details.html" class="btn btn-secondary"><i class="fa fa-angle-double-right"></i> Details</a></td>
                              </tr>
                          </tbody>
                      </table>
                    </div>
                    </div>
                  <div class="col-md-3">
                    <div class="card text-center bg-primary text-white mb-3">
                      <div class="card-body">
                         <h3>Posts</h3>
                          <h1 class="display-4">
                          <i class="fa fa-pencil"></i> 6
                          </h1>
                          <a href="posts.html" class="btn btn-outline-light btn-sm">View</a>
                        </div>
                        </div>
                      
                      <div class="card text-center bg-success text-white mb-3">
                      <div class="card-body">
                         <h3>Categories</h3>
                          <h1 class="display-4">
                          <i class="fa fa-folder-open-o"></i> 4
                          </h1>
                          <a href="categories.html" class="btn btn-outline-light btn-sm">View</a>
                        </div>
                  </div>
                      
                      <div class="card text-center bg-warning text-white mb-3">
                      <div class="card-body">
                         <h3>Users</h3>
                          <h1 class="display-4">
                          <i class="fa fa-users"></i> 2
                          </h1>
                          <a href="users.html" class="btn btn-outline-light btn-sm">View</a>
                        </div>
                  </div>
             </div>
        </div>
            </div>
        
        </section>
        
        <!--Footer-->
        <footer id="main-footer bg-dark text-white mt-5 p-5">
          <div class="container">
            <div class="row">
              <div class="col">
                <p class="lead text-center">Copyright &copy; 2018 Waetech Solutions</p>
                </div>
              </div>
            </div>
        </footer>
        
        
        
        <!--Post Modal Section-->
        
        <div class="modal fade" id="addPostModal">
          <div class="modal-dialog modal-lg">
             <div class="modal-content">
               <div class="modal-header bg-primary text-white">
                 <h5 class="modal-title">Add Post</h5>
                   <button class="close" data-dismiss="modal">
                   <span>&times;</span>
                   </button>
                 </div>
                 <div class="modal-body">
                 <form>
                     <div class="form-group">
                       <label for="title">Title</label>
                         <input type="text" class="form-control">
                     </div>
                     <div class="form-group">
                       <label for="category">Category</label>
                         <select class="form-control">
                            <option value="">Web Developement</option>
                             <option value="">Tech Gadgets</option>
                             <option value="">Business</option>
                             <option value="">Health & Wellness</option>
                              </select>
                         </div>
                     <div class="form-group">
                       <label for="file">Image Upload</label>
                         <input type="file" class="form-control-file">
                         <small class="form-text text-muted">Max Size 3MB</small>
                     </div>
                     <div class="form-group">
                       <label for="body">Body</label>
                         <textarea name="editor" class="form-control" id="editor"></textarea>
                     </div>
                     </form>
                 </div>
                 <div class="modal-footer">
                   <button class="btn btn-secondary" data-dismiss="modal">Close</button>
                     <button class="btn btn-primary" data-dismiss="modal">Save Changes</button>
                 </div>
                 
              </div>
            </div>
        </div>
        
        
        
        <!--Category Modal Section-->
        
        <div class="modal fade" id="addCategoryModal">
          <div class="modal-dialog modal-lg">
             <div class="modal-content">
               <div class="modal-header bg-success text-white">
                 <h5 class="modal-title">Add Category</h5>
                   <button class="close" data-dismiss="modal">
                   <span>&times;</span>
                   </button>
                 </div>
                 <div class="modal-body">
                 <form>
                     <div class="form-group">
                       <label for="title">Title</label>
                         <input type="text" class="form-control">
                     </div>
                     <div class="form-group">
                       <label for="category">Category</label>
                         <select class="form-control">
                            <option value="">Web Developement</option>
                             <option value="">Tech Gadgets</option>
                             <option value="">Business</option>
                             <option value="">Health & Wellness</option>
                              </select>
                         </div>
                     <div class="form-group">
                       <label for="file">Image Upload</label>
                         <input type="file" class="form-control-file">
                         <small class="form-text text-muted">Max Size 3MB</small>
                     </div>
                     <div class="form-group">
                       <label for="body">Body</label>
                         <textarea name="editor" class="form-control" id="editor"></textarea>
                     </div>
                     </form>
                 </div>
                 <div class="modal-footer">
                   <button class="btn btn-secondary" data-dismiss="modal">Close</button>
                     <button class="btn btn-primary" data-dismiss="modal">Save Changes</button>
                 </div>
                 
              </div>
            </div>
        </div>
        
        <!--Add User Modal-->
        
        <div class="modal fade" id="addUserModal">
          <div class="modal-dialog modal-lg">
             <div class="modal-content">
               <div class="modal-header bg-warning text-white">
                 <h5 class="modal-title">Add User</h5>
                   <button class="close" data-dismiss="modal">
                   <span>&times;</span>
                   </button>
                 </div>
                 <div class="modal-body">
                 <form>
                     <div class="form-group">
                       <label for="name">Name</label>
                         <input type="text" class="form-control">
                     </div>
                     <div class="form-group">
                       <label for="name">Email</label>
                         <input type="email" class="form-control">
                     </div>
                     <div class="form-group">
                       <label for="name">Password</label>
                         <input type="password" class="form-control">
                     </div>
                     <div class="form-group">
                       <label for="name">Confirm Password</label>
                         <input type="password" class="form-control">
                     </div>
                     </form>
                 </div>
                
                 <div class="modal-footer">
                   <button class="btn btn-secondary" data-dismiss="modal">Close</button>
                     <button class="btn btn-warning" data-dismiss="modal">Save Changes</button>
                 </div>
                 
              </div>
            </div>
        </div>
        
        
        
    <script src="js/jquery.min.js"></script>
     <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
        <script src="https://cdn.ckeditor.com/ckeditor5/1.0.0-alpha.2/classic/ckeditor.js"></script>
        <script>
			ClassicEditor
				.create( document.querySelector( '#editor' ) )
				.then( editor => {
					console.log( editor );
				} )
				.catch( error => {
					console.error( error );
				} );
		</script>
    
    </body>
</html>
