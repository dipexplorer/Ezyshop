## Project Structure ✨

<!-- START_STRUCTURE -->
```
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── PROJECT_STRUCTURE.md
├── README.md
├── SECURITY.md
├── actions/
│   ├── cart-actions.tsx
│   ├── get-categories.tsx
│   ├── get-products.tsx
│   ├── get-seller.tsx
│   └── wishlist-actions.tsx
├── app/
│   ├── (Customer)/
│   │   ├── (footerPages)/
│   │   │   ├── (T&C)/
│   │   │   │   ├── Policy/
│   │   │   │   │   └── page.tsx
│   │   │   │   └── Terms/
│   │   │   │       └── page.tsx
│   │   │   └── contributors/
│   │   │       └── page.tsx
│   │   ├── About/
│   │   │   └── page.tsx
│   │   ├── Blog/
│   │   │   ├── [blogId]/
│   │   │   │   └── page.tsx
│   │   │   └── page.tsx
│   │   ├── Cart/
│   │   │   ├── components/
│   │   │   │   ├── cart-item.tsx
│   │   │   │   └── summary.tsx
│   │   │   ├── loading.tsx
│   │   │   └── page.tsx
│   │   ├── Categories/
│   │   │   └── page.tsx
│   │   ├── Contact/
│   │   │   └── page.tsx
│   │   ├── MyOrders/
│   │   │   ├── [orderId]/
│   │   │   │   └── page.tsx
│   │   │   ├── components/
│   │   │   │   ├── columns.tsx
│   │   │   │   ├── datatable.tsx
│   │   │   │   ├── orderCard.tsx
│   │   │   │   └── orderItem.tsx
│   │   │   └── page.tsx
│   │   ├── Teams/
│   │   │   └── page.tsx
│   │   ├── WishList/
│   │   │   ├── components/
│   │   │   │   └── wishlistItem.tsx
│   │   │   └── page.tsx
│   │   ├── auth/
│   │   │   ├── components/
│   │   │   │   ├── loginPage.tsx
│   │   │   │   └── signupPage.tsx
│   │   │   ├── customer/
│   │   │   │   └── page.tsx
│   │   │   └── role/
│   │   │       └── page.tsx
│   │   ├── fonts/
│   │   │   ├── GeistMonoVF.woff
│   │   │   └── GeistVF.woff
│   │   ├── layout.tsx
│   │   ├── loading.tsx
│   │   ├── page.tsx
│   │   └── shops/
│   │       ├── [storeId]/
│   │       │   ├── components/
│   │       │   │   ├── ProductForm.tsx
│   │       │   │   └── filter.tsx
│   │       │   └── page.tsx
│   │       └── page.tsx
│   ├── (Seller)/
│   │   ├── [sellerId]/
│   │   │   ├── [storeId]/
│   │   │   │   ├── billboards/
│   │   │   │   │   ├── [billboardId]/
│   │   │   │   │   │   ├── components/
│   │   │   │   │   │   │   └── billboard-form.tsx
│   │   │   │   │   │   └── page.tsx
│   │   │   │   │   ├── components/
│   │   │   │   │   │   ├── cell-action.tsx
│   │   │   │   │   │   ├── client.tsx
│   │   │   │   │   │   └── columns.tsx
│   │   │   │   │   └── page.tsx
│   │   │   │   ├── categories/
│   │   │   │   │   ├── [categoryId]/
│   │   │   │   │   │   ├── components/
│   │   │   │   │   │   │   └── category-form.tsx
│   │   │   │   │   │   └── page.tsx
│   │   │   │   │   ├── components/
│   │   │   │   │   │   ├── cell-action.tsx
│   │   │   │   │   │   ├── client.tsx
│   │   │   │   │   │   └── columns.tsx
│   │   │   │   │   └── page.tsx
│   │   │   │   ├── components/
│   │   │   │   │   └── storeNav.tsx
│   │   │   │   ├── dashboard/
│   │   │   │   │   ├── edit/
│   │   │   │   │   │   ├── components/
│   │   │   │   │   │   │   └── dashboard-form.tsx
│   │   │   │   │   │   └── page.tsx
│   │   │   │   │   └── page.tsx
│   │   │   │   ├── layout.tsx
│   │   │   │   └── products/
│   │   │   │       ├── [productId]/
│   │   │   │       │   ├── components/
│   │   │   │       │   │   └── product-form.tsx
│   │   │   │       │   └── page.tsx
│   │   │   │       ├── components/
│   │   │   │       │   ├── cell-action.tsx
│   │   │   │       │   ├── client.tsx
│   │   │   │       │   └── columns.tsx
│   │   │   │       └── page.tsx
│   │   │   ├── components/
│   │   │   │   ├── sellerDashboard.tsx
│   │   │   │   ├── setupStore.tsx
│   │   │   │   └── storeCard.tsx
│   │   │   ├── layout.tsx
│   │   │   └── page.tsx
│   │   ├── auth/
│   │   │   ├── components/
│   │   │   │   ├── loginPage.tsx
│   │   │   │   └── signupPage.tsx
│   │   │   └── seller/
│   │   │       └── page.tsx
│   │   └── layout.tsx
│   ├── api/
│   │   ├── [sellerId]/
│   │   │   ├── [storeId]/
│   │   │   │   ├── billboards/
│   │   │   │   │   ├── [billboardId]/
│   │   │   │   │   │   └── route.ts
│   │   │   │   │   └── route.ts
│   │   │   │   ├── categories/
│   │   │   │   │   ├── [categoryId]/
│   │   │   │   │   │   └── route.ts
│   │   │   │   │   └── route.ts
│   │   │   │   ├── products/
│   │   │   │   │   ├── [productId]/
│   │   │   │   │   │   └── route.ts
│   │   │   │   │   └── route.ts
│   │   │   │   └── route.ts
│   │   │   └── route.ts
│   │   ├── auth/
│   │   │   ├── [...nextauth]/
│   │   │   │   └── route.ts
│   │   │   ├── login/
│   │   │   │   ├── seller/
│   │   │   │   │   └── route.ts
│   │   │   │   └── user/
│   │   │   │       └── route.ts
│   │   │   └── signup/
│   │   │       ├── route.ts
│   │   │       └── seller/
│   │   │           └── route.ts
│   │   └── getAllStores/
│   │       └── route.ts
│   ├── favicon.ico
│   ├── globals.css
│   ├── layout.tsx
│   └── not-found.tsx
├── components/
│   ├── Blog/
│   │   ├── Blog.tsx
│   │   ├── BlogCard.tsx
│   │   ├── CategoryByKeyword.tsx
│   │   ├── Comments.tsx
│   │   ├── RecentPosts.tsx
│   │   ├── RelatedPosts.tsx
│   │   ├── SubBlog.tsx
│   │   ├── blogAvatar.tsx
│   │   └── commentCard.tsx
│   ├── Maps/
│   │   ├── LazyMapWithPin.tsx
│   │   ├── LazyStaticMap.tsx
│   │   ├── mapWithPin.tsx
│   │   ├── mapWithPinComp.tsx
│   │   ├── popupStaticMap.tsx
│   │   └── staticMap.tsx
│   ├── Navbar/
│   │   ├── authButtons.tsx
│   │   ├── main-nav.tsx
│   │   ├── navbar.tsx
│   │   ├── seller-main-nav.tsx
│   │   └── sellerNav.tsx
│   ├── Testimonials.tsx
│   ├── about us/
│   │   └── learnAboutUs.tsx
│   ├── categories.tsx
│   ├── contactUsForm.tsx
│   ├── contributorCard.tsx
│   ├── features.tsx
│   ├── footer.tsx
│   ├── modals/
│   │   ├── alert-modal.tsx
│   │   ├── authModal.tsx
│   │   ├── flashAlert.tsx
│   │   └── store-modal.tsx
│   ├── setUpGuide/
│   │   ├── main.tsx
│   │   ├── pgs/
│   │   │   ├── FormControl.tsx
│   │   │   ├── coverUrlForm.tsx
│   │   │   ├── mapLocationForm.tsx
│   │   │   └── storeForm.tsx
│   │   ├── sideBarConstants.tsx
│   │   └── sidebar.tsx
│   ├── shops/
│   │   ├── clientSearchBar.tsx
│   │   ├── productCard.tsx
│   │   └── shopCard.tsx
│   └── ui/
│       ├── Hero.tsx
│       ├── ItemNotFound.tsx
│       ├── ScrollToTop.tsx
│       ├── alert.tsx
│       ├── api-alert.tsx
│       ├── api-list.tsx
│       ├── avatar.tsx
│       ├── badge.tsx
│       ├── button.tsx
│       ├── card.tsx
│       ├── carousel.tsx
│       ├── checkbox.tsx
│       ├── combobox.tsx
│       ├── command.tsx
│       ├── data-table.tsx
│       ├── dialog.tsx
│       ├── dropdown-menu.tsx
│       ├── form.tsx
│       ├── heading.tsx
│       ├── image-upload.tsx
│       ├── input-otp.tsx
│       ├── input.tsx
│       ├── label.tsx
│       ├── modal.tsx
│       ├── popover.tsx
│       ├── select.tsx
│       ├── separator.tsx
│       ├── seperatorHeading.tsx
│       ├── spinner.tsx
│       ├── table.tsx
│       ├── teamMember.tsx
│       ├── textarea.tsx
│       ├── themeButton.tsx
│       └── use-origin.tsx
├── components.json
├── context/
│   ├── cartContext.tsx
│   ├── flashAlertContext.tsx
│   ├── storeContext.tsx
│   └── themeProvider.tsx
├── hooks/
│   └── use-origin.tsx
├── lib/
│   ├── auth.ts
│   ├── nodemailerConfig.ts
│   ├── prismadb.ts
│   ├── sendEmail.ts
│   └── utils.ts
├── next.config.mjs
├── package-lock.json
├── package.json
├── postcss.config.mjs
├── prisma/
│   ├── schema.prisma
│   └── seed.ts
├── providers/
│   └── sessionProvider.tsx
├── public/
│   ├── Founder.jpeg
│   ├── about-us-1.png
│   ├── about-us-2.png
│   ├── anita.jpg
│   ├── bg-sidebar-desktop.svg
│   ├── bg-sidebar-desktop2.svg
│   ├── bg-sidebar-mobile.svg
│   ├── blog-1.png
│   ├── blog-2.png
│   ├── blog-3.png
│   ├── categories/
│   │   ├── Automotive&Tools.webp
│   │   ├── BabyProducts&Maternity.webp
│   │   ├── Beauty&PersonalCare.webp
│   │   ├── Books&Media.webp
│   │   ├── Health&Wellness.webp
│   │   ├── Home&Living.webp
│   │   ├── PetSupplies.webp
│   │   ├── Sports&Fitness.webp
│   │   ├── Toyes2.png
│   │   ├── class-1.png
│   │   ├── class-2.png
│   │   └── class-3.png
│   ├── contact.png
│   ├── detailblog.png
│   ├── electronics.png
│   ├── ezyshop.png
│   ├── fasion.png
│   ├── groceries.png
│   ├── hero.png
│   ├── not-found.png
│   ├── priya.jpg
│   ├── products/
│   │   ├── 1.jpeg
│   │   ├── 10.jpeg
│   │   ├── 11.jpeg
│   │   ├── 12.jpeg
│   │   ├── 13.jpeg
│   │   ├── 14.jpeg
│   │   ├── 15.jpeg
│   │   ├── 16.jpeg
│   │   ├── 17.jpeg
│   │   ├── 18.jpeg
│   │   ├── 19.jpeg
│   │   ├── 2.jpeg
│   │   ├── 20.jpeg
│   │   ├── 21.jpeg
│   │   ├── 22.jpeg
│   │   ├── 23.jpeg
│   │   ├── 24.jpeg
│   │   ├── 25.jpeg
│   │   ├── 26.jpeg
│   │   ├── 27.jpeg
│   │   ├── 3.jpeg
│   │   ├── 4.jpeg
│   │   ├── 5.jpeg
│   │   ├── 6.jpeg
│   │   ├── 7.jpeg
│   │   ├── 76.jpeg
│   │   ├── 78.jpeg
│   │   ├── 8.jpeg
│   │   ├── 9.jpeg
│   │   ├── avacado.webp
│   │   ├── banana.webp
│   │   ├── cola.avif
│   │   ├── eggs.avif
│   │   ├── happydent.avif
│   │   ├── limcee.avif
│   │   ├── mseal.avif
│   │   ├── product-image-not-available.png
│   │   └── tomato.avif
│   ├── rajesh.jpg
│   ├── shops/
│   │   ├── automative_image1.jpg
│   │   ├── babystore_image1.jpg
│   │   ├── bookstore_image1.jpg
│   │   ├── fashion_image1.jpg
│   │   ├── fashion_image2.jpg
│   │   ├── grocery_image1.jpg
│   │   ├── grocery_image2.jpg
│   │   ├── pet_image1.jpg
│   │   ├── tech_image1.jpg
│   │   ├── tech_image2.jpg
│   │   ├── toystore_image1.jpeg
│   │   └── wellness_image1.jpg
│   ├── storeSetupGreen.svg
│   ├── storeSetupTeal.svg
│   └── tailwind.config.js
├── repo_structure.txt
├── tailwind.config.ts
├── tsconfig.json
└── types/
    └── next-auth.d.ts
```
<!-- END_STRUCTURE -->