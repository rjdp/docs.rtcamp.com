---
title: rtp_set_footer_widget_grid_class
---

Add or modify footer widgets class.

    
    function custom_rtp_set_footer_widget_grid_class() {
        return "large-3 small-6 columns custom-footer-widget-class";
    }
    add_filter( 'rtp_set_footer_widget_grid_class', 'custom_rtp_set_footer_widget_grid_class' );
