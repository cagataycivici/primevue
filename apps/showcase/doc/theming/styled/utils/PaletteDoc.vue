<template>
    <DocSectionText v-bind="$attrs">
        <p>Returns shades and tints of a given color from 50 to 950 as an object.</p>
    </DocSectionText>
    <DocSectionCode :code="code" hideToggleCode importCode hideStackBlitz />
</template>

<script>
export default {
    data() {
        return {
            code: {
                basic: `
import { palette } from '@primeuix/themes';

// custom color
const values1 = palette('#10b981');

// copy an existing token set
const primaryColor = palette('{blue}');
`
            }
        };
    }
};
</script>
