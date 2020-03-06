<template lang="html">
    <div>
        <div class="mensaje">
            {{ mensaje }}
        </div>
    </div>
</template>

<script>
export default {
data() {
        return {
            mensaje: "© 2020 FIDE International Chess Federation. All Rights Reserved. No part of this site may be reproduced, stored in a retrieval system or transmitted in any way or by any means(including photocopying, recording or storing it in any medium by electronic means), without the written permission of FIDE International Chess Federation."
        }
    }
};
</script>

<style lang="scss" scoped>
$color_fondo: #334166;
$color_letras: #687A88;

div {
    background-color: $color_fondo;
    height: 80px;
    margin-top: 12px;

    .mensaje {
        color: #687A88;
        text-align:center;
    }
}
</style>