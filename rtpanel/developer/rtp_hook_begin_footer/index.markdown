---
title: rtp_hook_begin_footer
---

### Description


Adds content at the beginning of #footer-wrapper.


### Example



    
    function custom_rtp_hook_begin_footer() { ?>
    <p>This is the beginning of #footer-wrapper.</p><?php
    }
    add_action( 'rtp_hook_begin_footer', 'custom_rtp_hook_begin_footer' );
