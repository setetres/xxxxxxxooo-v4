<template>
    <div class="flex flex-col flex-1">
        <header aria-labelledby="header-heading" class="flex flex-col flex-1">
            <h2 id="header-heading" class="sr-only">Header</h2>
            <div class="flex-1 relative px-24 py-12 mx-24 my-24">
                <Logo />
            </div>
        </header>
        <div class="px-24 py-12 border-t border-zinc-700 bg-zinc-900">
            <Navigation />
            <Footer />
        </div>
    </div>
</template>