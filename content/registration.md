---
title: "Registration"
date: 2023-03-28T15:14:55-04:00
draft: false
---
<div class="row justify-content-center">
      <div class="col-md-8">
        <div class="card">
           <div class="card-header">Sign Up</div>
           <div class="card-body">
              <template v-if="showSuccess">
                <div class="text-bg-success">{{successMessage}}</div>
              </template>
              <template v-if="error">
                <div class="text-bg-danger">{{error}}</div>
              </template>
              <form @submit.prevent="submit">
              <div class="row my-3">
                <label class="form-label">Email</label>
                <div class="col-sm-10">
                  <input type="text" v-model="email" :rules="[rules.emailRule]" label="Email" autocomplete="username" class="form-control" placeholder="name@example.com">
                </div>
              </div>
              <div class="row my-3">
                <label class="form-label">Password</label>
                <div class="col-sm-10">
                  <input type="password" v-model="password" autocomplete="new-password" class="form-control">
                </div>
              </div>
              <div class="row my-3">
                <label class="form-label">I want to be a volunteer</label>
                <div class="col-sm-10">
                  <input type="checkbox" v-model="password" autocomplete="new-password" class="form-check-input">
                </div>
              </div>
              <button type="submit" class="btn btn-primary">Submit</button>
              <a href="/forgot-password" class="m-3">Forgot Password?</a>
              <a href="/login" class="m-3">Sign In</a>
              </form>
           </div>
        </div>
      </div>
</div>
