<template>
    <div class="nav-tab-wrapper tabs  section-padding">
        <div class="container">
            <div class="grid grid-cols-12 gap-[30px]">
                <div class="lg:col-span-8 col-span-12">
                    <SingleBlogCard />
                    <!-- comments start -->
                    <SingleBlogComments />
                    <!-- Reply start -->
                    <SingleBlogReplyCard />
                </div>
                <div class="lg:col-span-4 col-span-12">


                  <SingleBlogSidebar/>
                </div>
            </div>
        </div>
    </div>
</template>