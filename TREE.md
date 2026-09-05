
```
KIEL HELMET SHOP
├─ client
│  ├─ eslint.config.js
│  ├─ index.html
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ public
│  │  └─ vite.svg
│  ├─ README.md
│  ├─ src
│  │  ├─ App.css
│  │  ├─ App.jsx
│  │  ├─ assets
│  │  │  ├─ assortment.png
│  │  │  ├─ banner-mobile1.png
│  │  │  ├─ bannerg.png
│  │  │  ├─ bannerg1.png
│  │  │  ├─ default_user_profiles.png
│  │  │  ├─ delivery.png
│  │  │  ├─ documentlogo.png
│  │  │  ├─ empty_cart.png
│  │  │  ├─ KielHelmetShop.png
│  │  │  ├─ KielHelmetShop2.png
│  │  │  ├─ login_background_mobile.jfif
│  │  │  ├─ money.png
│  │  │  ├─ nothinghereyet.png
│  │  │  └─ react.svg
│  │  ├─ common
│  │  │  └─ SummaryApi.js
│  │  ├─ components
│  │  │  ├─ AddToCartButton.jsx
│  │  │  ├─ AdminActionModal.jsx
│  │  │  ├─ CancelOrderConfirm.jsx
│  │  │  ├─ CardProduct.jsx
│  │  │  ├─ CartSideDrawer.jsx
│  │  │  ├─ CategoryListing.jsx
│  │  │  ├─ CategoryWiseProductDisplay.jsx
│  │  │  ├─ Chatbot.jsx
│  │  │  ├─ CustomerManagement.jsx
│  │  │  ├─ DeleteCategoryConfirm.jsx
│  │  │  ├─ DeleteOrderConfirm.jsx
│  │  │  ├─ DeleteProductConfirm.jsx
│  │  │  ├─ DeleteSubCategoryConfirm.jsx
│  │  │  ├─ DownloadPreviewModal.jsx
│  │  │  ├─ EditCategory.jsx
│  │  │  ├─ EditProductAdmin.jsx
│  │  │  ├─ EditSubCategory.jsx
│  │  │  ├─ Footer.jsx
│  │  │  ├─ Header.jsx
│  │  │  ├─ Loading.jsx
│  │  │  ├─ NoData.jsx
│  │  │  ├─ PageLoadingFallback.jsx
│  │  │  ├─ ReviewModal.jsx
│  │  │  ├─ ScrollToTop.jsx
│  │  │  ├─ Search.jsx
│  │  │  ├─ SidebarMenu.jsx
│  │  │  ├─ Skeletons.jsx
│  │  │  ├─ UploadCategoryModel.jsx
│  │  │  ├─ UploadSubCategoryModel.jsx
│  │  │  ├─ UserAvatarUpload.jsx
│  │  │  ├─ UserMenu.jsx
│  │  │  └─ VariationModal.jsx
│  │  ├─ hooks
│  │  │  └─ useMobile.jsx
│  │  ├─ index.css
│  │  ├─ layouts
│  │  │  ├─ adminPermission.jsx
│  │  │  ├─ Dashboard.jsx
│  │  │  └─ superAdminPermission.jsx
│  │  ├─ main.jsx
│  │  ├─ pages
│  │  │  ├─ AboutUs.jsx
│  │  │  ├─ AdminOrders.jsx
│  │  │  ├─ AdminProducts.jsx
│  │  │  ├─ Adress.jsx
│  │  │  ├─ CategoryPage.jsx
│  │  │  ├─ CheckEmail.jsx
│  │  │  ├─ CheckoutPage.jsx
│  │  │  ├─ DisplayProductPage.jsx
│  │  │  ├─ FavoritePage.jsx
│  │  │  ├─ ForgotPassword.jsx
│  │  │  ├─ Home.jsx
│  │  │  ├─ Login.jsx
│  │  │  ├─ MyOrders.jsx
│  │  │  ├─ OrderDetails.jsx
│  │  │  ├─ OrderSuccessPage.jsx
│  │  │  ├─ PrivacyPolicy.jsx
│  │  │  ├─ ProductListPage.jsx
│  │  │  ├─ Profile.jsx
│  │  │  ├─ Register.jsx
│  │  │  ├─ ResetPassword.jsx
│  │  │  ├─ SearchPage.jsx
│  │  │  ├─ SubCategoryPage.jsx
│  │  │  ├─ SuperAdminSettings.jsx
│  │  │  ├─ TermsOfService.jsx
│  │  │  ├─ UploadProductPage.jsx
│  │  │  ├─ UserMenuMobile.jsx
│  │  │  ├─ VerifyEmail.jsx
│  │  │  └─ VerifyOtp.jsx
│  │  ├─ route
│  │  │  └─ index.jsx
│  │  ├─ store
│  │  │  ├─ cartSlice.js
│  │  │  ├─ store.js
│  │  │  └─ userSlice.js
│  │  └─ utils
│  │     ├─ Axios.js
│  │     ├─ AxiosToastError.js
│  │     ├─ DisplayPrice.js
│  │     ├─ fetchCartItems.js
│  │     ├─ fetcher.js
│  │     ├─ fetchUserData.js
│  │     ├─ generateOrderSummary.js
│  │     ├─ generateWaybill.js
│  │     ├─ isAdmin.js
│  │     ├─ isSuperAdmin.js
│  │     ├─ OptimizeImage.js
│  │     └─ UploadImage.js
│  └─ vite.config.js
├─ package-lock.json
├─ package.json
├─ README.md
├─ server
│  ├─ config
│  │  ├─ connectDB.js
│  │  ├─ sendEmail.js
│  │  └─ stripe.js
│  ├─ controllers
│  │  ├─ cart.controller.js
│  │  ├─ category.controller.js
│  │  ├─ chat.controller.js
│  │  ├─ order.controller.js
│  │  ├─ product.controller.js
│  │  ├─ review.controller.js
│  │  ├─ subCategory.controller.js
│  │  ├─ superadmin.controller.js
│  │  ├─ uploadImagesController.js
│  │  └─ user.controller.js
│  ├─ error_log.txt
│  ├─ index.js
│  ├─ logo_result.json
│  ├─ logo_url.txt
│  ├─ middleware
│  │  ├─ admin.js
│  │  ├─ auth.js
│  │  ├─ chatLimiter.js
│  │  ├─ multer.js
│  │  ├─ rateLimiter.js
│  │  └─ superadmin.js
│  ├─ models
│  │  ├─ category.model.js
│  │  ├─ emailSettings.model.js
│  │  ├─ order.model.js
│  │  ├─ product.model.js
│  │  ├─ review.model.js
│  │  ├─ subCategory.model.js
│  │  └─ user.model.js
│  ├─ models.json
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ route
│  │  ├─ cart.route.js
│  │  ├─ category.route.js
│  │  ├─ chat.route.js
│  │  ├─ order.route.js
│  │  ├─ product.route.js
│  │  ├─ review.route.js
│  │  ├─ subCategory.route.js
│  │  ├─ superadmin.route.js
│  │  ├─ upload.route.js
│  │  └─ user.route.js
│  ├─ tmp_upload_logo.js
│  └─ utils
│     ├─ forgotPasswordTemplate.js
│     ├─ generatedAccessToken.js
│     ├─ generatedOtp.js
│     ├─ generatedRefreshToken.js
│     ├─ newOrderAdminTemplate.js
│     ├─ orderCancelledAdminTemplate.js
│     ├─ orderReceiptTemplate.js
│     ├─ orderStatusUpdateTemplate.js
│     ├─ uploadImageCloudinary.js
│     └─ verifyEmailTemplate.js
└─ vercel.json

```
```
KIEL HELMET SHOP
├─ client
│  ├─ eslint.config.js
│  ├─ index.html
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ public
│  │  └─ vite.svg
│  ├─ README.md
│  ├─ src
│  │  ├─ App.css
│  │  ├─ App.jsx
│  │  ├─ assets
│  │  │  ├─ assortment.png
│  │  │  ├─ banner-mobile1.png
│  │  │  ├─ bannerg.png
│  │  │  ├─ bannerg1.png
│  │  │  ├─ default_user_profiles.png
│  │  │  ├─ delivery.png
│  │  │  ├─ documentlogo.png
│  │  │  ├─ empty_cart.png
│  │  │  ├─ KielHelmetShop.png
│  │  │  ├─ KielHelmetShop2.png
│  │  │  ├─ login_background_mobile.jfif
│  │  │  ├─ money.png
│  │  │  ├─ nothinghereyet.png
│  │  │  └─ react.svg
│  │  ├─ common
│  │  │  └─ SummaryApi.js
│  │  ├─ components
│  │  │  ├─ AddToCartButton.jsx
│  │  │  ├─ AdminActionModal.jsx
│  │  │  ├─ CancelOrderConfirm.jsx
│  │  │  ├─ CardProduct.jsx
│  │  │  ├─ CartSideDrawer.jsx
│  │  │  ├─ CategoryListing.jsx
│  │  │  ├─ CategoryWiseProductDisplay.jsx
│  │  │  ├─ Chatbot.jsx
│  │  │  ├─ CustomerManagement.jsx
│  │  │  ├─ DeleteCategoryConfirm.jsx
│  │  │  ├─ DeleteOrderConfirm.jsx
│  │  │  ├─ DeleteProductConfirm.jsx
│  │  │  ├─ DeleteSubCategoryConfirm.jsx
│  │  │  ├─ DownloadPreviewModal.jsx
│  │  │  ├─ EditCategory.jsx
│  │  │  ├─ EditProductAdmin.jsx
│  │  │  ├─ EditSubCategory.jsx
│  │  │  ├─ Footer.jsx
│  │  │  ├─ Header.jsx
│  │  │  ├─ Loading.jsx
│  │  │  ├─ NoData.jsx
│  │  │  ├─ PageLoadingFallback.jsx
│  │  │  ├─ ReviewModal.jsx
│  │  │  ├─ ScrollToTop.jsx
│  │  │  ├─ Search.jsx
│  │  │  ├─ SidebarMenu.jsx
│  │  │  ├─ Skeletons.jsx
│  │  │  ├─ UploadCategoryModel.jsx
│  │  │  ├─ UploadSubCategoryModel.jsx
│  │  │  ├─ UserAvatarUpload.jsx
│  │  │  ├─ UserMenu.jsx
│  │  │  └─ VariationModal.jsx
│  │  ├─ hooks
│  │  │  └─ useMobile.jsx
│  │  ├─ index.css
│  │  ├─ layouts
│  │  │  ├─ adminPermission.jsx
│  │  │  ├─ Dashboard.jsx
│  │  │  └─ superAdminPermission.jsx
│  │  ├─ main.jsx
│  │  ├─ pages
│  │  │  ├─ AboutUs.jsx
│  │  │  ├─ AdminOrders.jsx
│  │  │  ├─ AdminProducts.jsx
│  │  │  ├─ Adress.jsx
│  │  │  ├─ CategoryPage.jsx
│  │  │  ├─ CheckEmail.jsx
│  │  │  ├─ CheckoutPage.jsx
│  │  │  ├─ DisplayProductPage.jsx
│  │  │  ├─ FavoritePage.jsx
│  │  │  ├─ ForgotPassword.jsx
│  │  │  ├─ Home.jsx
│  │  │  ├─ Login.jsx
│  │  │  ├─ MyOrders.jsx
│  │  │  ├─ OrderDetails.jsx
│  │  │  ├─ OrderSuccessPage.jsx
│  │  │  ├─ PrivacyPolicy.jsx
│  │  │  ├─ ProductListPage.jsx
│  │  │  ├─ Profile.jsx
│  │  │  ├─ Register.jsx
│  │  │  ├─ ResetPassword.jsx
│  │  │  ├─ SearchPage.jsx
│  │  │  ├─ SubCategoryPage.jsx
│  │  │  ├─ SuperAdminSettings.jsx
│  │  │  ├─ TermsOfService.jsx
│  │  │  ├─ UploadProductPage.jsx
│  │  │  ├─ UserMenuMobile.jsx
│  │  │  ├─ VerifyEmail.jsx
│  │  │  └─ VerifyOtp.jsx
│  │  ├─ route
│  │  │  └─ index.jsx
│  │  ├─ store
│  │  │  ├─ cartSlice.js
│  │  │  ├─ store.js
│  │  │  └─ userSlice.js
│  │  └─ utils
│  │     ├─ Axios.js
│  │     ├─ AxiosToastError.js
│  │     ├─ DisplayPrice.js
│  │     ├─ fetchCartItems.js
│  │     ├─ fetcher.js
│  │     ├─ fetchUserData.js
│  │     ├─ generateOrderSummary.js
│  │     ├─ generateWaybill.js
│  │     ├─ isAdmin.js
│  │     ├─ isSuperAdmin.js
│  │     ├─ OptimizeImage.js
│  │     └─ UploadImage.js
│  └─ vite.config.js
├─ package-lock.json
├─ package.json
├─ README.md
├─ server
│  ├─ config
│  │  ├─ connectDB.js
│  │  ├─ sendEmail.js
│  │  └─ stripe.js
│  ├─ controllers
│  │  ├─ cart.controller.js
│  │  ├─ category.controller.js
│  │  ├─ chat.controller.js
│  │  ├─ order.controller.js
│  │  ├─ product.controller.js
│  │  ├─ review.controller.js
│  │  ├─ subCategory.controller.js
│  │  ├─ superadmin.controller.js
│  │  ├─ uploadImagesController.js
│  │  └─ user.controller.js
│  ├─ error_log.txt
│  ├─ index.js
│  ├─ logo_result.json
│  ├─ logo_url.txt
│  ├─ middleware
│  │  ├─ admin.js
│  │  ├─ auth.js
│  │  ├─ chatLimiter.js
│  │  ├─ multer.js
│  │  ├─ rateLimiter.js
│  │  └─ superadmin.js
│  ├─ models
│  │  ├─ category.model.js
│  │  ├─ emailSettings.model.js
│  │  ├─ order.model.js
│  │  ├─ product.model.js
│  │  ├─ review.model.js
│  │  ├─ subCategory.model.js
│  │  └─ user.model.js
│  ├─ models.json
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ route
│  │  ├─ cart.route.js
│  │  ├─ category.route.js
│  │  ├─ chat.route.js
│  │  ├─ order.route.js
│  │  ├─ product.route.js
│  │  ├─ review.route.js
│  │  ├─ subCategory.route.js
│  │  ├─ superadmin.route.js
│  │  ├─ upload.route.js
│  │  └─ user.route.js
│  ├─ tmp_upload_logo.js
│  └─ utils
│     ├─ forgotPasswordTemplate.js
│     ├─ generatedAccessToken.js
│     ├─ generatedOtp.js
│     ├─ generatedRefreshToken.js
│     ├─ newOrderAdminTemplate.js
│     ├─ orderCancelledAdminTemplate.js
│     ├─ orderReceiptTemplate.js
│     ├─ orderStatusUpdateTemplate.js
│     ├─ uploadImageCloudinary.js
│     └─ verifyEmailTemplate.js
├─ TREE.md
└─ vercel.json

```