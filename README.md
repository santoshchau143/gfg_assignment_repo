# gfg_assignment_repo
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Bootstrap Form</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CDN -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
  </head>

  <body class="bg-light">
    <div class="container mt-5">
      <div class="row justify-content-center">
        <div class="col-md-6">
          <div class="card shadow">
            <div class="card-body">
              <h3 class="text-center mb-4">Student Record</h3>

              <!-- FORM START -->
              <form action="#" method="post">
                <!-- Name -->
                <div class="mb-3">
                  <label class="form-label">Name</label>
                  <input
                    type="text"
                    name="name"
                    class="form-control"
                    required
                  />
                </div>

                <!-- Email -->
                <div class="mb-3">
                  <label class="form-label">Email</label>
                  <input
                    type="email"
                    name="email"
                    class="form-control"
                    required
                  />
                </div>

                <!-- Password -->
                <div class="mb-3">
                  <label class="form-label">Password</label>
                  <input
                    type="password"
                    name="password"
                    class="form-control"
                    required
                  />
                </div>

                <!-- Gender -->
                <div class="mb-3">
                  <label class="form-label">Gender</label>
                  <select name="gender" class="form-select">
                    <option value="">Select</option>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                  </select>
                </div>
                <!--Course-->
                <div class="mb-3">
                  <label class="form-label">Course</label>
                  <select name="course" class="form-select">
                    <option value="">Select</option>
                    <option value="b.tech">B.Tech</option>
                    <option value="m.tech">M.Tech</option>
                    <option value="bca">BCA</option>
                    <option value="mca">MCA</option>
                    <option value="bba">BBA</option>
                    <option value="mba">MBA</option>
                    <option value="b.sc">B.Sc</option>
                    <option value="m.sc">M.Sc</option>
                    <option value="ba">BA</option>
                    <option value="ma">MA</option>
                    
                  </select>
                </div>
                <!--Year-->
                <div class="mb-3">
                  <label class="form-label">Year</label>
                  <select name="year" class="form-select">
                    <option value="">Select</option>
                    <option value="first">First Year</option>
                    <option value="second">Second Year</option>
                    <option value="third">Third Year</option>
                    <option value="four">Forth Year</option>

                  </select>
                </div>

                <!-- Checkbox -->
                <div class="form-check mb-3">
                  <input class="form-check-input" type="checkbox" required />
                  <label class="form-check-label">
                    Accept terms & conditions
                  </label>
                </div>

                <!-- Submit -->
                <button type="submit" class="btn btn-primary w-100">
                  Submit
                </button>
              </form>
              <!-- FORM END -->
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
