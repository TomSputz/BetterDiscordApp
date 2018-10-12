/**
 * BetterDiscord Settings Anchor Component
 * Copyright (c) 2015-present Jiiks/JsSucks - https://github.com/Jiiks / https://github.com/JsSucks
 * All rights reserved.
 * https://betterdiscord.net
 *
 * This source code is licensed under the MIT license found in the
 * LICENSE file in the root directory of this source tree.
*/
// Rewrite of the BdSettings layout that is made to: Anchor properly in the dom, and have the settingsButton nested inside the sidebar so as to allow smooth animation.
<template>
    <div class="bd-settingsWrapper" :class="[{'bd-active': active}, 'platform-' + this.platform]">
        
    </div>
</template>