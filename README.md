{
  "settings": {
    "name": "My Site",
    "currentPage": "gpi5.html",
    "theme": {
      "name": "mobirise4",
      "title": "Mobirise 4",
      "styling": {
        "primaryColor": "#149dcc",
        "secondaryColor": "#ff3366",
        "successColor": "#F7ED4A",
        "infoColor": "#82786E",
        "warningColor": "#879A9F",
        "dangerColor": "#B1A374",
        "mainFont": "Rubik",
        "display1Font": "Rubik",
        "display1Size": 4.25,
        "display2Font": "Rubik",
        "display2Size": 3,
        "display5Font": "Rubik",
        "display5Size": 1.5,
        "display7Font": "Rubik",
        "display7Size": 1,
        "display4Font": "Rubik",
        "display4Size": 1,
        "isRoundedButtons": true,
        "isAnimatedOnScroll": false,
        "isScrollToTopButton": false
      },
      "additionalSetColors": []
    },
    "path": "@PROJECT_PATH@",
    "siteFonts": [],
    "versionFirst": "4.7.6",
    "uniqCompNum": 70,
    "versionPublish": "4.10.15",
    "screenshot": "screenshot.png",
    "favicon": "",
    "noImageResize": ""
  },
  "pages": {
    "page1.html": {
      "settings": {
        "meta_descr": "Web Site Creator Description",
        "title": "Entregables",
        "order": 6
      },
      "components": [
        {
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "-webkit-flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".navbar-expand": {
                "flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#333333\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"gpi5.html\">\n                         <img src=\"@PROJECT_PATH@/assets/images/icono-1-192x192.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\" title>\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"gpi5.html\" data-app-placeholder=\"Type Text\">Grupo 5</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\"><li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.com\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">\n                        </a>\n                </li>\n                <li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page5.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Problema</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page2.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Usuario</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page3.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Estado del Arte</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page4.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">La Propuesta</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page1.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Entregables</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page6.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Bibliografía</a></li></ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\"><a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a></div>\n        </div>\n    </nav>\n</section>",
          "_cid": "qTkzRZLJNu",
          "_anchor": "menu1-b",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            }
          },
          "_name": "header2",
          "_customHTML": "<section group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{\n         'mbr-fullscreen': fullScreen,\n         'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#073B4C\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container align-center\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    Entregables</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Aquí encontrará los entregables realizados por el grupo</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-success\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">Entregable 1</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">Entregable 2</a> <a class=\"btn btn-md btn-success\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">Entregable 3</a></div>\n            </div>\n        </div>\n    </div>\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "rFfJAomtV3",
          "_anchor": "header2-y",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            ".content": {
              "@media (max-width: 767px)": {
                "text-align": "center",
                "> div:not(:last-child)": {
                  "margin-bottom": "2rem"
                }
              }
            },
            ".media-wrap": {
              "@media (max-width: 767px)": {
                "margin-bottom": "1rem"
              },
              ".mbr-iconfont-logo": {
                "font-size": "7.5rem",
                "color": "#f36"
              },
              "img": {
                "height": "6rem"
              }
            },
            ".footer-lower": {
              ".copyright": {
                "@media (max-width: 767px)": {
                  "margin-bottom": "1rem",
                  "text-align": "center"
                }
              },
              "hr": {
                "margin": "1rem 0",
                "border-color": "#fff",
                "opacity": ".05"
              },
              ".social-list": {
                "padding-left": "0",
                "margin-bottom": "0",
                "list-style": "none",
                "display": "flex",
                "flex-wrap": "wrap",
                "justify-content": "flex-end",
                "-webkit-justify-content": "flex-end",
                ".mbr-iconfont-social": {
                  "font-size": "1.3rem",
                  "color": "#fff"
                },
                ".soc-item": {
                  "margin": "0 .5rem"
                },
                "a": {
                  "margin": "0",
                  "opacity": ".5",
                  "-webkit-transition": ".2s linear",
                  "transition": ".2s linear",
                  "&:hover": {
                    "opacity": "1"
                  }
                },
                "@media (max-width: 767px)": {
                  "justify-content": "center",
                  "-webkit-justify-content": "center"
                }
              }
            }
          },
          "_name": "footer1",
          "_customHTML": "<section group=\"Footers\" mbr-class=\"{'mbr-reveal': reveal, 'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->  \n        <input type=\"range\" inline=\"\" title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline=\"\" title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"checkbox\" title=\"Show Copyright\" name=\"showCopyright\" checked=\"\">\n        <select title=\"Icons\" name=\"iconsCount\">\n            <option value=\"0\" selected=\"\">0</option>\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\">6</option>\n        </select>\n        <input type=\"checkbox\" title=\"Reveal effect\" name=\"reveal\">\n        <fieldset type=\"background\" name=\"bg\" parallax=\"\">\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#2e2e2e\" selected=\"\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked=\"\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#3C3C3C\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n        <input type=\"range\" inline=\"\" title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay &amp;&amp; bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row content text-white\">\n            <div class=\"col-12 col-md-3\">\n                <div class=\"media-wrap\">\n                    <a href=\"https://mobirise.com/\">\n                        <img src=\"@PROJECT_PATH@/assets/images/icono-192x192.png\" alt=\"Mobirise\" title=\"\">\n                    </a>\n                </div>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">&nbsp; &nbsp;</h5>\n                <p class=\"mbr-text\">&nbsp; &nbsp;</p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Contáctanos</h5>\n                <p class=\"mbr-text\">\n                    Email: pibgrupo5@gmail.com&nbsp;<br><br><br></p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\"><p>&nbsp;<br></p></h5>\n                <p class=\"mbr-text\">&nbsp;&nbsp;</p>\n            </div>\n        </div>\n        <div class=\"footer-lower\" mbr-if=\"showCopyright\">\n            <div class=\"media-container-row\">\n                <div class=\"col-sm-12\">\n                    <hr>\n                </div>\n            </div>\n            <div class=\"media-container-row mbr-white\">\n                <div class=\"col-sm-6 copyright\">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".copyright > p\">\n                        © Copyright 2017 Mobirise - All Rights Reserved\n                    </p>\n                </div>\n                <div class=\"col-md-6\">\n                    <div class=\"social-list align-right\" mbr-if=\"iconsCount > 0\">\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>0\">\n                            <a href=\"https://twitter.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"mbr-iconfont mbr-iconfont-social socicon-googleplus socicon\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>1\">\n                            <a href=\"https://www.facebook.com/pages/Mobirise/1616226671953247\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-facebook socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>2\">\n                            <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-youtube socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>3\">\n                            <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-instagram socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>4\">\n                            <a href=\"https://plus.google.com/u/0/+Mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-googleplus socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>5\">\n                            <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-behance socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_anchor": "footer1-18",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "rFfPiJ7Uqv",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "page2.html": {
      "settings": {
        "meta_descr": "Site Builder Description",
        "title": "Usuario",
        "order": 3
      },
      "components": [
        {
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "-webkit-flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".navbar-expand": {
                "flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#333333\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"gpi5.html\">\n                         <img src=\"@PROJECT_PATH@/assets/images/icono-1-192x192.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\" title>\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"gpi5.html\" data-app-placeholder=\"Type Text\">Grupo 5</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\"><li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.com\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">\n                        </a>\n                </li>\n                <li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page5.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Problema</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page2.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Usuario</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page3.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Estado del Arte</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page4.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">La Propuesta</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page1.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Entregables</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page6.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Bibliografía</a></li></ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\"><a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a></div>\n        </div>\n    </nav>\n</section>",
          "_cid": "qTkzRZLJNu",
          "_anchor": "menu1-c",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            }
          },
          "_name": "header1",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/diabetes-capa-1-730x457.png\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#7f1933\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#073b4c\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title align-center mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    EL USUARIO</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">Adulto diabético</h3>\n                <p class=\"mbr-text align-center pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Nos dirigimos al adulto que presenta diabetes mellitus tipo 2. Con la conidicón de que posee neuropatía diabética y posible riesgo de amputación</p>\n                <div class=\"mbr-section-btn align-center\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\"><a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">\n                        <span class=\"mbr-iconfont mbri-file\"></span>LEARN MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "rFaZreceSD",
          "_anchor": "header1-m",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            ".mbr-text, blockquote": {
              "color": "#767676"
            }
          },
          "_name": "content1",
          "_customHTML": "<section class=\"mbr-section article content1\">\n    \n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Width Content\" name=\"widthContent\" min=\"1\" max=\"4\" step=\"1\" value=\"2\">\n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#ffffff\">\n    <!-- End block parameters -->\n    </mbr-parameters> \n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"mbr-text col-12 mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\" data-multiline mbr-article mbr-class=\"{'col-md-6': widthContent == 1, 'col-md-8': widthContent == 2, 'col-md-10': widthContent == 3, 'col-md-12': widthContent == 4}\"><p><b>Segmento de mercado:</b></p><p><b>-Trabajos:\n</b></p><div>&nbsp; &nbsp; -<b>Funcionales: </b>trabajar, desempeñarse profesionalmente, asistir a sus controles médicos.<b>\n</b></div><div>&nbsp; &nbsp; -<b>Sociales: </b>cuidar su estado físico y emocional, mostrarse como personas sanas.\n</div><div>&nbsp;&nbsp;&nbsp;&nbsp;<span style=\"font-size: 1rem;\">-</span><b style=\"font-size: 1rem;\">Personales o emocionales: </b><span style=\"font-size: 1rem;\">llevar una buena calidad de vida, mantener un adecuado nivel </span><span style=\"font-size: 1rem;\">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style=\"font-size: 1rem;\">&nbsp;&nbsp;&nbsp;&nbsp;de insulina en su organismo.&nbsp;</span></div><div><b style=\"font-size: 1rem;\">-Frustraciones:&nbsp;</b></div><div>&nbsp;&nbsp;&nbsp;&nbsp;<b>-Funcionales: </b>mal estado de los equipos o servicios con los que se trata, gasto excesivo &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;en tratamientos y diálisis.\n</div><div>&nbsp;&nbsp;&nbsp;&nbsp;<b>-Sociales: </b>mal manejo de la enfermedad, ser discriminado por su condición y enfermedad.\n</div><div>&nbsp; &nbsp; -<b>Secundaria: </b>tiempo perdido en traslados hacia el lugar de sus consultas.\n</div><div>&nbsp; &nbsp; -<b>Obstáculos: </b>falta de tiempo para asistir a sus controles, dejar de seguir con su dieta &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;asignada.\n</div><div>&nbsp; &nbsp; -<b>Riesgos:</b>&nbsp;desarrollar otras complicaciones derivadas de la enfermedad, como la &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;neuropatía o problemas oculares.\n</div><div><b>-Alegrías:\n</b></div><div>&nbsp; &nbsp; -<b>Necesarias: </b>recibir atención médica de calidad<b>\n</b></div><div>&nbsp; &nbsp; -<b>Esperadas: </b>mejora en su condición médica <b>\n</b></div><div>&nbsp; &nbsp; -<b>Deseadas: </b>mejorar completamente su condición, eliminar la enfermedad\n</div><div>&nbsp; &nbsp; -<b>Inesperadas: </b>conocer su enfermedad y cómo seguir su tratamiento sin necesidad de&nbsp;un doctor presente (diagnóstico y análisis a distancia)\n</div><div><b><br></b></div><div><b>Propuesta de valor:\n</b></div><div><b>-Productos y servicios:\n</b></div><div>&nbsp; &nbsp; -<b>Físicos y tangibles: </b>sensor para una detección de las venas o zonas de su cuerpo más &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;afectadas.\n</div><div>&nbsp;&nbsp;&nbsp;&nbsp;<b>-Intangibles: </b>mayor accesibilidad a sus servicios<b> \n</b></div><div>&nbsp;&nbsp;&nbsp;&nbsp;<b>-Digitales: </b>sistema de diagnóstico y análisis a distancia\n</div><div>&nbsp;&nbsp;&nbsp;&nbsp;<b>-Financieros: </b>apoyo económico por parte del seguro para solventar su tratamiento clínico \n</div><div><b>-Creadores de alegrías: </b>mejora de su condición física, poder llevar una condición de vida &nbsp;&nbsp;&nbsp;&nbsp;“normal”, menos tiempo trasladándose.\n</div><div><b>-Aliviadores de frustraciones: </b>sistema a distancia evita pérdida de tiempo en transporte, &nbsp;&nbsp;&nbsp;&nbsp;mejor diagnóstico médico qué otros métodos convencionales, apoyo económico evita gastos &nbsp;&nbsp;&nbsp;&nbsp;excesivos por parte del paciente.\n</div><div><b><br></b></div><p></p></div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFaZVvvha8",
          "_anchor": "content1-o",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "background": "@bgColor",
            "& when (@fullWidth = false)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@gradientBg)": {
              "background": "linear-gradient(45deg, @bgColor, @color2)"
            },
            ".image-block": {
              "margin": "auto",
              "& when (@fullWidth)": {
                "width": "100% !important"
              }
            },
            ".mbr-figure": {
              "margin": "0 auto"
            },
            "figcaption": {
              "position": "relative",
              "div": {
                "position": "absolute",
                "bottom": "0",
                "width": "100%"
              }
            },
            "@media (max-width: 768px)": {
              ".image-block": {
                "width": "100% !important"
              }
            },
            ".mbr-figure-caption div": {
              "color": "#232323",
              "text-align": "left"
            }
          },
          "_name": "image2",
          "_customHTML": "<section group=\"Images & Videos\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Width\" name=\"fullWidth\" checked>\n\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" value=\"4\" step=\"1\" condition=\"fullWidth==false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" value=\"4\" step=\"1\" condition=\"fullWidth==false\">\n\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>        \n        \n        <input type=\"range\" inline title=\"Width\" name=\"imageSize\" min=\"20\" max=\"100\" value=\"100\" step=\"1\" condition=\"fullWidth==false\">\n\n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#ffffff\" condition=\"fullWidth==false\">\n        <input type=\"checkbox\" title=\"Gradient\" name=\"gradientBg\" condition=\"fullWidth==false\">\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#149dcc\" condition=\"gradientBg && fullWidth==false\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <figure class=\"mbr-figure\" mbr-class=\"{'container':fullWidth==false}\">\n        <div class=\"image-block\" mbr-style=\"{'width':imageSize+'%'}\">\n            <img src=\"@PROJECT_PATH@/assets/images/procesos-1324x746.png\" alt=\"Mobirise\" title>\n            <figcaption class=\"mbr-figure-caption mbr-figure-caption-over\" mbr-if=\"showText\">\n                <div mbr-text class=\"pb-5 px-3 mbr-white align-center mbr-fonts-style\" mbr-theme-style=\"display-1\" data-app-selector=\".mbr-figure-caption div\">\n                    Mapa de valor</div>\n            </figcaption>\n        </div>\n    </figure>\n</section>",
          "_cid": "rFfOJDUYSA",
          "_anchor": "image2-16",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            ".content": {
              "@media (max-width: 767px)": {
                "text-align": "center",
                "> div:not(:last-child)": {
                  "margin-bottom": "2rem"
                }
              }
            },
            ".media-wrap": {
              "@media (max-width: 767px)": {
                "margin-bottom": "1rem"
              },
              ".mbr-iconfont-logo": {
                "font-size": "7.5rem",
                "color": "#f36"
              },
              "img": {
                "height": "6rem"
              }
            },
            ".footer-lower": {
              ".copyright": {
                "@media (max-width: 767px)": {
                  "margin-bottom": "1rem",
                  "text-align": "center"
                }
              },
              "hr": {
                "margin": "1rem 0",
                "border-color": "#fff",
                "opacity": ".05"
              },
              ".social-list": {
                "padding-left": "0",
                "margin-bottom": "0",
                "list-style": "none",
                "display": "flex",
                "flex-wrap": "wrap",
                "justify-content": "flex-end",
                "-webkit-justify-content": "flex-end",
                ".mbr-iconfont-social": {
                  "font-size": "1.3rem",
                  "color": "#fff"
                },
                ".soc-item": {
                  "margin": "0 .5rem"
                },
                "a": {
                  "margin": "0",
                  "opacity": ".5",
                  "-webkit-transition": ".2s linear",
                  "transition": ".2s linear",
                  "&:hover": {
                    "opacity": "1"
                  }
                },
                "@media (max-width: 767px)": {
                  "justify-content": "center",
                  "-webkit-justify-content": "center"
                }
              }
            }
          },
          "_name": "footer1",
          "_customHTML": "<section group=\"Footers\" mbr-class=\"{'mbr-reveal': reveal, 'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->  \n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"checkbox\" title=\"Show Copyright\" name=\"showCopyright\" checked>\n        <select title=\"Icons\" name=\"iconsCount\">\n            <option value=\"0\" selected>0</option>\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\">6</option>\n        </select>\n        <input type=\"checkbox\" title=\"Reveal effect\" name=\"reveal\">\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#2e2e2e\" selected>\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#3C3C3C\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row content text-white\">\n            <div class=\"col-12 col-md-3\">\n                <div class=\"media-wrap\">\n                    <a href=\"https://mobirise.com/\">\n                        <img src=\"@PROJECT_PATH@/assets/images/icono-192x192.png\" alt=\"Mobirise\" title>\n                    </a>\n                </div>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">&nbsp; &nbsp;</h5>\n                <p class=\"mbr-text\">&nbsp; &nbsp;</p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Contáctanos</h5>\n                <p class=\"mbr-text\">\n                    Email: pibgrupo5@gmail.com&nbsp;<br><br><br></p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\"><p>&nbsp;<br></p></h5>\n                <p class=\"mbr-text\">&nbsp;&nbsp;</p>\n            </div>\n        </div>\n        <div class=\"footer-lower\" mbr-if=\"showCopyright\">\n            <div class=\"media-container-row\">\n                <div class=\"col-sm-12\">\n                    <hr>\n                </div>\n            </div>\n            <div class=\"media-container-row mbr-white\">\n                <div class=\"col-sm-6 copyright\">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".copyright > p\">\n                        © Copyright 2017 Mobirise - All Rights Reserved\n                    </p>\n                </div>\n                <div class=\"col-md-6\">\n                    <div class=\"social-list align-right\" mbr-if=\"iconsCount > 0\">\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>0\">\n                            <a href=\"https://twitter.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"mbr-iconfont mbr-iconfont-social socicon-googleplus socicon\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>1\">\n                            <a href=\"https://www.facebook.com/pages/Mobirise/1616226671953247\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-facebook socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>2\">\n                            <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-youtube socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>3\">\n                            <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-instagram socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>4\">\n                            <a href=\"https://plus.google.com/u/0/+Mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-googleplus socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>5\">\n                            <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-behance socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_anchor": "footer1-15",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "rFfOFbGBx6",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "background": "@bgColor",
            "& when (@fullWidth = false)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@gradientBg)": {
              "background": "linear-gradient(45deg, @bgColor, @color2)"
            },
            ".image-block": {
              "margin": "auto",
              "& when (@fullWidth)": {
                "width": "100% !important"
              }
            },
            ".mbr-figure": {
              "margin": "0 auto"
            },
            "figcaption": {
              "position": "relative",
              "div": {
                "position": "absolute",
                "bottom": "0",
                "width": "100%"
              }
            },
            "@media (max-width: 768px)": {
              ".image-block": {
                "width": "100% !important"
              }
            },
            ".mbr-figure-caption div": {
              "color": "#cc2952"
            }
          },
          "_name": "image2",
          "_customHTML": "<section group=\"Images & Videos\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Width\" name=\"fullWidth\" checked>\n\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" value=\"4\" step=\"1\" condition=\"fullWidth==false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" value=\"4\" step=\"1\" condition=\"fullWidth==false\">\n\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>        \n        \n        <input type=\"range\" inline title=\"Width\" name=\"imageSize\" min=\"20\" max=\"100\" value=\"100\" step=\"1\" condition=\"fullWidth==false\">\n\n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#ffffff\" condition=\"fullWidth==false\">\n        <input type=\"checkbox\" title=\"Gradient\" name=\"gradientBg\" condition=\"fullWidth==false\">\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#149dcc\" condition=\"gradientBg && fullWidth==false\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <figure class=\"mbr-figure\" mbr-class=\"{'container':fullWidth==false}\">\n        <div class=\"image-block\" mbr-style=\"{'width':imageSize+'%'}\">\n            <img src=\"@PROJECT_PATH@/assets/images/mapa-de-valor-958x507.png\" alt=\"Mobirise\" title>\n            <figcaption class=\"mbr-figure-caption mbr-figure-caption-over\" mbr-if=\"showText\">\n                <div mbr-text class=\"pb-5 px-3 mbr-white align-center mbr-fonts-style\" mbr-theme-style=\"display-1\" data-app-selector=\".mbr-figure-caption div\"><b>\n                    </b><br><br><br><b>Mapa de valor del </b><b>usuario</b><b><br></b><br><br><br><br><br><br><br><b><br></b></div>\n            </figcaption>\n        </div>\n    </figure>\n</section>",
          "_cid": "rFaZQkW4NS",
          "_anchor": "image2-n",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "page3.html": {
      "settings": {
        "meta_descr": "Web Builder Description",
        "title": "Estado del Arte",
        "order": 4
      },
      "components": [
        {
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "-webkit-flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".navbar-expand": {
                "flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#333333\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"gpi5.html\">\n                         <img src=\"@PROJECT_PATH@/assets/images/icono-1-192x192.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\" title>\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"gpi5.html\" data-app-placeholder=\"Type Text\">Grupo 5</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\"><li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.com\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">\n                        </a>\n                </li>\n                <li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page5.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Problema</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page2.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Usuario</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page3.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Estado del Arte</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page4.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">La Propuesta</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page1.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Entregables</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page6.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Bibliografía</a></li></ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\"><a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a></div>\n        </div>\n    </nav>\n</section>",
          "_cid": "qTkzRZLJNu",
          "_anchor": "menu1-d",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-figure": {
              "margin": "0 auto",
              "width": "100%",
              "display": "-webkit-flex",
              "justify-content": "center",
              "-webkit-justify-content": "center",
              "img": {
                "height": "100%",
                "margin": "0 auto"
              }
            },
            "@media (max-width: 991px)": {
              ".mbr-figure": {
                "img": {
                  "width": "100% !important"
                }
              }
            },
            "H1": {
              "color": "#232323"
            },
            ".mbr-text, .mbr-section-btn": {
              "color": "#232323"
            }
          },
          "_name": "header4",
          "_customHTML": "<section class=\"header4\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n        <input type=\"range\" inline title=\"Media Size\" name=\"mediaSize\" min=\"10\" max=\"100\" step=\"5\" value=\"60\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background1.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#f7ed4a\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.8\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"media-content col-md-10\">\n                <h1 class=\"mbr-section-title align-center mbr-white pb-3 mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    ESTADO DEL ARTE</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-white mbr-light pb-3 mbr-fonts-style\" mbr-if=\"showSubTitle\" mbr-theme-style=\"display-2\">\n                    Beautiful mobile websites\n                </h3>\n                <div class=\"mbr-text align-center mbr-white pb-3\">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-if=\"showText\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-text, .mbr-section-btn\">Según el usuario que hemos visto, vimos propuestas relacionadas</p>\n                </div>\n                <div class=\"mbr-section-btn align-center\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\">\n                    <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.co\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.co\">LIVE DEMO</a>\n                </div>\n            </div>\n            <div class=\"mbr-figure pt-5\">\n                <img src=\"@PROJECT_PATH@/assets/images/diabetes-sp17-980x587.jpg\" alt=\"Mobirise\" mbr-style=\"{'width': mediaSize + '%'}\" title>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFb1Qmiq6P",
          "_anchor": "header4-q",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            "& when (@reverseContent)": {
              "@media (min-width: 992px)": {
                ".mbr-figure": {
                  "padding-left": "4rem"
                }
              },
              "@media (max-width: 992px)": {
                ".mbr-figure": {
                  "padding-top": "1rem"
                }
              }
            },
            "& when not (@reverseContent)": {
              ".media-container-row": {
                "flex-direction": "row-reverse",
                "-webkit-flex-direction": "row-reverse"
              },
              "@media (min-width: 992px)": {
                ".mbr-figure": {
                  "padding-right": "4rem"
                }
              },
              "@media (max-width: 991px)": {
                ".media-container-row": {
                  "flex-wrap": "wrap-reverse",
                  "-webkit-flex-wrap": "wrap-reverse"
                },
                ".mbr-figure": {
                  "padding-bottom": "1rem"
                }
              }
            },
            ".mbr-text": {
              "color": "#767676"
            }
          },
          "_name": "content7",
          "_customHTML": "<section class=\"mbr-section content7\" group=\"Article\">\n          \n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->   \n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Media Size\" name=\"mediaSize\" min=\"10\" max=\"200\" step=\"5\" value=\"60\">\n        <input type=\"range\" inline title=\"Width Content\" name=\"widthContent\" min=\"1\" max=\"4\" step=\"1\" value=\"2\">\n        <input type=\"checkbox\" title=\"Text On Right/Left\" name=\"reverseContent\" checked> \n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#ffffff\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"col-12\" mbr-class=\"{'col-md-6': widthContent == 1, 'col-md-8': widthContent == 2, 'col-md-10': widthContent == 3, 'col-md-12': widthContent == 4}\">\n                <div class=\"media-container-row\">\n                    <div class=\"media-content\">\n                        <div class=\"mbr-section-text\">\n                            <p class=\"mbr-text align-right mb-0 mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\">\n                               <b>Minimed 640g</b>&nbsp;Bomba de insulina portátil y personalizable que puede regular los niveles de glucosa del paciente, llegando incluso a predecir y advertir si estos niveles están en riesgo o cantidades inadecuadas. Su precio es moderado, pero puede verse como caro para un paciente de clase social baja.</p>\n                        </div>\n                    </div>\n                    <div class=\"mbr-figure\" mbr-style=\"{'width': mediaSize + '%'}\">\n                     <img src=\"@PROJECT_PATH@/assets/images/maxresdefault-960x540.jpg\" alt=\"Mobirise\" title>  \n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFb2CZHIGc",
          "_anchor": "content7-s",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            "& when not (@reverseContent)": {
              "@media (min-width: 992px)": {
                ".mbr-figure": {
                  "padding-right": "4rem"
                }
              },
              "@media (max-width: 991px)": {
                ".mbr-figure": {
                  "padding-bottom": "1rem"
                }
              }
            },
            "& when (@reverseContent)": {
              ".media-container-row": {
                "flex-direction": "row-reverse",
                "-webkit-flex-direction": "row-reverse"
              },
              "@media (min-width: 992px)": {
                ".mbr-figure": {
                  "padding-left": "4rem"
                }
              },
              "@media (max-width: 991px)": {
                ".media-container-row": {
                  "flex-wrap": "wrap-reverse",
                  "-webkit-flex-wrap": "wrap-reverse"
                },
                ".mbr-figure": {
                  "padding-top": "1rem"
                }
              }
            },
            ".mbr-text": {
              "color": "#767676"
            }
          },
          "_name": "content6",
          "_customHTML": "<section class=\"mbr-section content6\" group=\"Article\">\n    \n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n      <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n      <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n\n      <input type=\"range\" inline title=\"Media Size\" name=\"mediaSize\" min=\"10\" max=\"200\" step=\"5\" value=\"60\">\n        <input type=\"checkbox\" title=\"Text On Right/Left\" name=\"reverseContent\">  \n      <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#f9f295\">\n    <!-- End block parameters -->\n    </mbr-parameters> \n    \n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"col-12 col-md-8\">\n                <div class=\"media-container-row\">\n                    <div class=\"mbr-figure\" mbr-style=\"{'width': mediaSize + '%'}\">\n                      <img src=\"@PROJECT_PATH@/assets/images/images-3-275x183.jpg\" alt=\"Mobirise\" title>  \n                    </div>\n                    <div class=\"media-content\">\n                        <div class=\"mbr-section-text\">\n                            <p class=\"mbr-text mb-0 mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\"><b>Imagen por resonancia magnética</b>&nbsp;A través de un proceso en el que el paciente se coloca en una cámara especial, se pueden obtener imágenes de alta resolución de distintos órganos del cuerpo</p>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFb2U9m3oV",
          "_anchor": "content6-t",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            "& when (@reverseContent)": {
              "@media (min-width: 992px)": {
                ".mbr-figure": {
                  "padding-left": "4rem"
                }
              },
              "@media (max-width: 992px)": {
                ".mbr-figure": {
                  "padding-top": "1rem"
                }
              }
            },
            "& when not (@reverseContent)": {
              ".media-container-row": {
                "flex-direction": "row-reverse",
                "-webkit-flex-direction": "row-reverse"
              },
              "@media (min-width: 992px)": {
                ".mbr-figure": {
                  "padding-right": "4rem"
                }
              },
              "@media (max-width: 991px)": {
                ".media-container-row": {
                  "flex-wrap": "wrap-reverse",
                  "-webkit-flex-wrap": "wrap-reverse"
                },
                ".mbr-figure": {
                  "padding-bottom": "1rem"
                }
              }
            },
            ".mbr-text": {
              "color": "#767676"
            }
          },
          "_name": "content7",
          "_customHTML": "<section class=\"mbr-section content7\" group=\"Article\">\n          \n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->   \n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Media Size\" name=\"mediaSize\" min=\"10\" max=\"200\" step=\"5\" value=\"60\">\n        <input type=\"range\" inline title=\"Width Content\" name=\"widthContent\" min=\"1\" max=\"4\" step=\"1\" value=\"2\">\n        <input type=\"checkbox\" title=\"Text On Right/Left\" name=\"reverseContent\" checked> \n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#ffffff\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"col-12\" mbr-class=\"{'col-md-6': widthContent == 1, 'col-md-8': widthContent == 2, 'col-md-10': widthContent == 3, 'col-md-12': widthContent == 4}\">\n                <div class=\"media-container-row\">\n                    <div class=\"media-content\">\n                        <div class=\"mbr-section-text\">\n                            <p class=\"mbr-text align-right mb-0 mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\">\n                               <b>Ecografía doppler</b>&nbsp;Se emiten ondas de alta frecuencia, las cuales rebotan en los vasos sanguíneos y permite calcular el flujo de sangre en estos. Es una tecnología con gran potencial para poder medir el nivel de glucosa en la sangre de un paciente. Se encuentra disponible en hospiales del país.</p>\n                        </div>\n                    </div>\n                    <div class=\"mbr-figure\" mbr-style=\"{'width': mediaSize + '%'}\">\n                     <img src=\"@PROJECT_PATH@/assets/images/lda-principle-487x362.jpg\" alt=\"Mobirise\" title>  \n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFb2V0qL3V",
          "_anchor": "content7-u",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            "& when not (@reverseContent)": {
              "@media (min-width: 992px)": {
                ".mbr-figure": {
                  "padding-right": "4rem"
                }
              },
              "@media (max-width: 991px)": {
                ".mbr-figure": {
                  "padding-bottom": "1rem"
                }
              }
            },
            "& when (@reverseContent)": {
              ".media-container-row": {
                "flex-direction": "row-reverse",
                "-webkit-flex-direction": "row-reverse"
              },
              "@media (min-width: 992px)": {
                ".mbr-figure": {
                  "padding-left": "4rem"
                }
              },
              "@media (max-width: 991px)": {
                ".media-container-row": {
                  "flex-wrap": "wrap-reverse",
                  "-webkit-flex-wrap": "wrap-reverse"
                },
                ".mbr-figure": {
                  "padding-top": "1rem"
                }
              }
            },
            ".mbr-text": {
              "color": "#767676"
            }
          },
          "_name": "content6",
          "_customHTML": "<section class=\"mbr-section content6\" group=\"Article\">\n    \n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n      <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n      <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n\n      <input type=\"range\" inline title=\"Media Size\" name=\"mediaSize\" min=\"10\" max=\"200\" step=\"5\" value=\"60\">\n        <input type=\"checkbox\" title=\"Text On Right/Left\" name=\"reverseContent\">  \n      <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#f9f295\">\n    <!-- End block parameters -->\n    </mbr-parameters> \n    \n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"col-12 col-md-8\">\n                <div class=\"media-container-row\">\n                    <div class=\"mbr-figure\" mbr-style=\"{'width': mediaSize + '%'}\">\n                      <img src=\"@PROJECT_PATH@/assets/images/exploracion-con-escaner-laser-obtiene-imagenes-del-seno-completo-650x650.jpg\" alt=\"Mobirise\" title>  \n                    </div>\n                    <div class=\"media-content\">\n                        <div class=\"mbr-section-text\">\n                            <p class=\"mbr-text mb-0 mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\">\n                               <b>Imágenes fotoacústicas&nbsp;</b>Mediante la emisión de pulsos de luz, la piel puede reaccionar, emitiendo ondas fotoacústicas. Estas son captadas por un transductor y procesadas paral luego ser convertidas en imágenes. Se estudia la posibilidad de su aplicación en diabetes.</p>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFb3pk5SQt",
          "_anchor": "content6-v",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            ".content": {
              "@media (max-width: 767px)": {
                "text-align": "center",
                "> div:not(:last-child)": {
                  "margin-bottom": "2rem"
                }
              }
            },
            ".media-wrap": {
              "@media (max-width: 767px)": {
                "margin-bottom": "1rem"
              },
              ".mbr-iconfont-logo": {
                "font-size": "7.5rem",
                "color": "#f36"
              },
              "img": {
                "height": "6rem"
              }
            },
            ".footer-lower": {
              ".copyright": {
                "@media (max-width: 767px)": {
                  "margin-bottom": "1rem",
                  "text-align": "center"
                }
              },
              "hr": {
                "margin": "1rem 0",
                "border-color": "#fff",
                "opacity": ".05"
              },
              ".social-list": {
                "padding-left": "0",
                "margin-bottom": "0",
                "list-style": "none",
                "display": "flex",
                "-webkit-flex-wrap": "wrap",
                "flex-wrap": "wrap",
                "-webkit-justify-content": "flex-end",
                "justify-content": "flex-end",
                ".mbr-iconfont-social": {
                  "font-size": "1.3rem",
                  "color": "#fff"
                },
                ".soc-item": {
                  "margin": "0 .5rem"
                },
                "a": {
                  "margin": "0",
                  "opacity": ".5",
                  "-webkit-transition": ".2s linear",
                  "transition": ".2s linear",
                  "&:hover": {
                    "opacity": "1"
                  }
                },
                "@media (max-width: 767px)": {
                  "-webkit-justify-content": "center",
                  "justify-content": "center"
                }
              }
            }
          },
          "_name": "footer1",
          "_customHTML": "<section group=\"Footers\" mbr-class=\"{'mbr-reveal': reveal, 'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->  \n        <input type=\"range\" inline=\"\" title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline=\"\" title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"checkbox\" title=\"Show Copyright\" name=\"showCopyright\" checked=\"\">\n        <select title=\"Icons\" name=\"iconsCount\">\n            <option value=\"0\">0</option>\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\" selected=\"\">6</option>\n        </select>\n        <input type=\"checkbox\" title=\"Reveal effect\" name=\"reveal\">\n        <fieldset type=\"background\" name=\"bg\" parallax=\"\">\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background5.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#2e2e2e\" selected=\"\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked=\"\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n        <input type=\"range\" inline=\"\" title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.8\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay &amp;&amp; bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row content text-white\">\n            <div class=\"col-12 col-md-3\">\n                <div class=\"media-wrap\">\n                    <a href=\"https://mobirise.co/\">\n                        <img src=\"../_images/logo2.png\" alt=\"Mobirise\">\n                    </a>\n                </div>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Address\n                </h5>\n                <p class=\"mbr-text\">\n                    1234 Street Name\n                    <br>City, AA 99999\n                </p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Contacts\n                </h5>\n                <p class=\"mbr-text\">\n                    Email: support@mobirise.com\n                    <br>Phone: +1 (0) 000 0000 001\n                    <br>Fax: +1 (0) 000 0000 002\n                </p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Links\n                </h5>\n                <p class=\"mbr-text\">\n                    <a class=\"text-primary\" href=\"https://mobirise.co/\">Website builder</a>\n                    <br><a class=\"text-primary\" href=\"https://mobirise.co/\">Download for Windows</a>\n                    <br><a class=\"text-primary\" href=\"https://mobirise.co/\">Download for Mac</a>\n                </p>\n            </div>\n        </div>\n        <div class=\"footer-lower\" mbr-if=\"showCopyright\">\n            <div class=\"media-container-row\">\n                <div class=\"col-sm-12\">\n                    <hr>\n                </div>\n            </div>\n            <div class=\"media-container-row mbr-white\">\n                <div class=\"col-sm-6 copyright\">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".copyright > p\">\n                        © Copyright 2019 Mobirise - All Rights Reserved\n                    </p>\n                </div>\n                <div class=\"col-md-6\">\n                    <div class=\"social-list align-right\" mbr-if=\"iconsCount > 0\">\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>0\">\n                            <a href=\"https://twitter.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-twitter socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>1\">\n                            <a href=\"https://www.facebook.com/pages/Mobirise/1616226671953247\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-facebook socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>2\">\n                            <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-youtube socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>3\">\n                            <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-instagram socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>4\">\n                            <a href=\"https://plus.google.com/u/0/+Mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-googleplus socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>5\">\n                            <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-behance socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>\n",
          "_cid": "rFb3B4zJSi",
          "_anchor": "footer1-w",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "page4.html": {
      "settings": {
        "meta_descr": "Website Builder Description",
        "title": "Propuesta",
        "order": 5
      },
      "components": [
        {
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "-webkit-flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".navbar-expand": {
                "flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#333333\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"gpi5.html\">\n                         <img src=\"@PROJECT_PATH@/assets/images/icono-1-192x192.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\" title>\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"gpi5.html\" data-app-placeholder=\"Type Text\">Grupo 5</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\"><li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.com\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">\n                        </a>\n                </li>\n                <li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page5.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Problema</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page2.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Usuario</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page3.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Estado del Arte</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page4.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">La Propuesta</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page1.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Entregables</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page6.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Bibliografía</a></li></ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\"><a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a></div>\n        </div>\n    </nav>\n</section>",
          "_cid": "qTkzRZLJNu",
          "_anchor": "menu1-e",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            }
          },
          "_name": "header1",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/diabetes-sp17-980x587.jpeg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#7f1933\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#149dcc\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title align-center mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    Propuesta&nbsp;</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text align-center pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">Uso de imágenes fotoacústicas desde un dispositvo móvil para tomar muestras de tejido necroso del paciente.</p>\n                <div class=\"mbr-section-btn align-center\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\"><a class=\"btn btn-md btn-secondary\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">\n                        <span class=\"mbr-iconfont mbri-file\"></span>LEARN MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "rFfKF92NR1",
          "_anchor": "header1-z",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "h3": {
              "text-align": "center"
            },
            ".mbr-section-subtitle": {
              "color": "#767676",
              "font-weight": "300"
            },
            ".mbr-content-text": {
              "color": "#767676"
            },
            ".panel-item when not (@transparentBg)": {
              "background": "@cardBg"
            },
            ".card": {
              "word-wrap": "break-word"
            },
            ".mbr-iconfont": {
              "font-size": "80px",
              "color": "#149dcc"
            }
          },
          "_name": "counters1",
          "_customHTML": "<section class=\"counters1 counters\" group=\"Counters\" plugins=\"ViewportChecker\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n\n        <input type=\"checkbox\" title=\"Show Block Title\" name=\"showTitles\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Icons\" name=\"showIcons\">\n\n        <select title=\"Cards Count\" name=\"cardsAmount\">\n           <option value=\"1\">1</option>\n           <option value=\"2\">2</option>\n           <option value=\"3\" selected>3</option>\n           <option value=\"4\">4</option>\n        </select>\n        \n        <input type=\"checkbox\" title=\"Transparent BG\" name=\"transparentBg\">\n        <input type=\"color\" title=\"Card Bg\" name=\"cardBg\" value=\"#ffffff\" condition=\"!transparentBg\">\n        \n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background2.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#f9f295\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#b2ccd2\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.9\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <h2 class=\"mbr-section-title pb-3 align-center mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title\">\n            Características</h2>\n        <h3 class=\"mbr-section-subtitle mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\">\n            Nuestro producto es:</h3>\n\n        <div class=\"container pt-4 mt-2\">\n            <div class=\"media-container-row\">\n                <div class=\"card p-3 align-center col-12 col-md-6\" mbr-class=\"{'col-lg-3': cardsAmount == '4','col-lg-4': cardsAmount == '3'}\">\n                    <div class=\"panel-item\" mbr-class=\"{'p-3':!transparentBg}\">\n                        <div class=\"card-img pb-3\" mbr-if=\"showIcons\">\n                            <span mbr-icon class=\"mbri-mobirise mbr-iconfont\"></span>\n                        </div>\n\n                        <div class=\"card-text\">\n                            <h3 class=\"count pt-3 pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\">\n                                  Innovador</h3>\n                            <h4 class=\"mbr-content-title mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitles\">\n                                Unlimited websites\n                            </h4>\n                            <p class=\"mbr-content-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\" data-app-selector=\".mbr-content-text\">\n                                Permite un dagnóstico rápido, efectivo y preciso de zona de piel del paciente a distancia y sin métodos invasivos.</p>\n                        </div>\n                    </div>\n                </div>\n\n\n                <div class=\"card p-3 align-center col-12 col-md-6\" mbr-if=\"cardsAmount>1\" mbr-class=\"{'col-lg-3': cardsAmount == '4','col-lg-4': cardsAmount == '3'}\">\n                    <div class=\"panel-item\" mbr-class=\"{'p-3':!transparentBg}\">\n                        <div class=\"card-img pb-3\" mbr-if=\"showIcons\">\n                            <span mbr-icon class=\"mbri-touch-swipe mbr-iconfont\"></span>\n                        </div>\n                        <div class=\"card-text\">\n                            <h3 class=\"count pt-3 pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\">Portátil</h3>\n                            <h4 class=\"mbr-content-title mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitles\">\n                                Trendy websites blocks\n                            </h4>\n                            <p class=\"mbr-content-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\" data-app-selector=\".mbr-content-text\">\n                                    Se conectará a un <i>smartphone </i>mediante un puerto mirco USB, lo que lo vuelve más sencillo de utilizar.</p>\n                        </div>\n                    </div>\n                </div>\n\n                <div class=\"card p-3 align-center col-12 col-md-6\" mbr-if=\"cardsAmount>2\" mbr-class=\"{'col-lg-3': cardsAmount == '4','col-lg-4': cardsAmount == '3'}\">\n                    <div class=\"panel-item\" mbr-class=\"{'p-3':!transparentBg}\">\n                        <div class=\"card-img pb-3\" mbr-if=\"showIcons\">\n                            <span mbr-icon class=\"mbri-responsive mbr-iconfont\"></span>\n                        </div>\n                        <div class=\"card-text\">\n                            <h3 class=\"count pt-3 pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\">\n                                  Telemedicina</h3>\n                            <h4 class=\"mbr-content-title mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitles\">\n                                Bootstrap\n                            </h4>\n                            <p class=\"mbr-content-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\" data-app-selector=\".mbr-content-text\">\n                                    El paciente y el médico tratante tendrán acceso a la información e imágenes tomadas en todo moemnto, lo que permitirá elaborar un diagnóstico adecuado a distancia.</p>\n                        </div>\n                    </div>\n                </div>\n\n\n                <div class=\"card p-3 align-center col-12 col-md-6\" mbr-if=\"cardsAmount>3\" mbr-class=\"{'col-lg-3': cardsAmount == '4','col-lg-4': cardsAmount == '3'}\">\n                    <div class=\"panel-item\" mbr-class=\"{'p-3':!transparentBg}\">\n                        <div class=\"card-img pb-3\" mbr-if=\"showIcons\">\n                            <span mbr-icon class=\"mbri-hot-cup mbr-iconfont\"></span>\n                        </div>\n\n                        <div class=\"card-texts\">\n                             <h3 class=\"count pt-3 pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\">\n                                  400\n                            </h3>\n                            <h4 class=\"mbr-content-title mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitles\">\n                                Web fonts\n                            </h4>\n                            <p class=\"mbr-content-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\" data-app-selector=\".mbr-content-text\">\n                                    Google has a highly exhaustive list of fonts compiled into its web font platform and Mobirise make it easy for you to use them on your website easily and freely\n                            </p>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n   </div>\n</section>",
          "_cid": "rFfKZfCno7",
          "_anchor": "counters1-10",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#efefef\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    VDI 2225</h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    La metodología de diseño aplicada a nuestro proyecto</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">LEARN MORE</a>\n                </div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "rFfL06VfMJ",
          "_anchor": "header16-11",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"0\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    FULL WIDTH INTRO\n                </h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Tabla de requerimientos</h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Full width intro with adjustable height, background image and a color overlay. Click any text to edit or style it.\n                </p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">LEARN MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "rFfLaywCgX",
          "_anchor": "header16-13",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            ".counter-container": {
              "color": "#767676",
              "ol": {
                "margin-bottom": "0",
                "li": {
                  "margin-bottom": "1rem"
                },
                "& when (@stylizedCounters)": {
                  "counter-reset": "myCounter",
                  "li": {
                    "list-style": "none",
                    "padding-left": ".5rem",
                    "&:before": {
                      "position": "absolute",
                      "left": "0px",
                      "margin-top": "-10px",
                      "counter-increment": "myCounter",
                      "content": "counter(myCounter)",
                      "display": "inline-block",
                      "text-align": "center",
                      "margin": "5px 10px",
                      "line-height": "40px",
                      "transition": "all .2s",
                      "color": "contrast(@counterColor)",
                      "background": "@counterColor",
                      "width": "40px",
                      "height": "40px",
                      "border-radius": "50%",
                      "& when (@squareCounters)": {
                        "border-radius": "0"
                      }
                    }
                  }
                }
              }
            }
          },
          "_name": "content11",
          "_customHTML": "<section class=\"mbr-section article content11\">\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"checkbox\" title=\"Stylized Counters\" name=\"stylizedCounters\" checked>\n        <input type=\"checkbox\" title=\"Square Counters\" name=\"squareCounters\" condition=\"stylizedCounters\">\n        <input type=\"color\" title=\"Counter Color\" name=\"counterColor\" value=\"#787324\" condition=\"stylizedCounters\">\n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#f9f295\">\n    <!-- End block parameters -->\n    </mbr-parameters> \n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"mbr-text counter-container col-12 col-md-8 mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\" data-multiline mbr-article>\n                <ol>\n                    <li><b>Estudio previo</b> - se requiere de conocer los valores estándar de ondas que emite la piel, comparando las de una persona sana con pacientes diabéticos en distintas etapas de su enfermedad.&nbsp;</li>\n                    <li><b>Valor de luz&nbsp;</b>- conocer con qué frecuencia de luz reaccionará la piel, dependiendo de cada zona del cuerpo esta podría variar</li>\n                    <li><b>Frecuencia de ultrasonido</b>&nbsp;- como las ondas fotoacústicas son a base de ultrasonido, esta emisión debe de ser mayor a 30KHz para una recepción de datos adecuada</li>\n                </ol>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFfL8x7O8F",
          "_anchor": "content11-12",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"0\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"0\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    FULL WIDTH INTRO\n                </h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Entradas y Salidas</h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Full width intro with adjustable height, background image and a color overlay. Click any text to edit or style it.\n                </p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">LEARN MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_anchor": "header16-1b",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "rFfQQiT3ZH",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "h4": {
              "text-align": "left",
              "font-weight": "500"
            },
            "p": {
              "color": "#767676",
              "text-align": "left",
              "margin-bottom": "0"
            },
            ".card-img": {
              "text-align": "left",
              "-webkit-flex": "1 0 auto",
              "flex": "1 0 auto",
              "width": "auto"
            },
            ".card-img span": {
              "font-size": "72px",
              "color": "rgb(255, 51, 102)"
            },
            ".card-box": {
              "padding-left": "1rem",
              "word-break": "break-word",
              "width": "100%"
            },
            "@media (max-width: 991px)": {
              ".card-img": {
                "text-align": "left",
                "padding-bottom": "0.75rem"
              },
              ".card-box": {
                "padding-left": "0"
              }
            }
          },
          "_name": "features9",
          "_customHTML": "<section class=\"features9\" group=\"Features\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <select title=\"Cards\" name=\"cardsAmount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\" selected>2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background5.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#f9f295\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset> \n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#efefef\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.8\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container\">\n        <div class=\"row justify-content-center\">\n            <div class=\"card p-3 col-12 col-md-6\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"media-container-row\">\n                    <div class=\"card-img pr-2\">\n                        <span mbr-icon class=\"mbr-iconfont mbri-login\"></span>\n                    </div>\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title, .card-img\">\n                            Entradas</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                           -Ultrasonido<br>-Ondas fotoacústicas</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"card p-3 col-12 col-md-6\" mbr-if=\"cardsAmount > 1\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"media-container-row\">\n                    <div class=\"card-img pr-2\">\n                        <span mbr-icon class=\"mbr-iconfont mbri-logout\"></span>\n                    </div>\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title, .card-img\">\n                            Salidas</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                           -Imágenes fotoacústicas<br>-Datos de la profundidad del tejido necroso en la zona donde se tomó la muestra</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"card p-3 col-12 col-md-6\" mbr-if=\"cardsAmount > 2\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"media-container-row\">\n                    <div class=\"card-img pr-2\">\n                        <span mbr-icon class=\"mbri-desktop mbr-iconfont\"></span>\n                    </div>\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title, .card-img\">\n                            Unique Styles\n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                           Mobirise offers many site blocks in several themes, and though these blocks are pre-made, they are flexible.\n                        </p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"card p-3 col-12 col-md-6\" mbr-if=\"cardsAmount > 3\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"media-container-row\">\n                    <div class=\"card-img pr-2\">\n                        <span mbr-icon class=\"mbri-touch mbr-iconfont\"></span>\n                    </div>\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title, .card-img\">\n                            Unlimited Sites\n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                           Mobirise gives you the freedom to develop as many websites as you like given the fact that it is a desktop app.\n                        </p>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFfQZLUi8X",
          "_anchor": "features9-1c",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"0\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"0\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    FULL WIDTH INTRO\n                </h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Esquema de funciones</h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Full width intro with adjustable height, background image and a color overlay. Click any text to edit or style it.\n                </p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">LEARN MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_anchor": "header16-1d",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "rFfRy05rBa",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".card-box": {
              "background-color": "@cardsBg",
              "padding": "2rem"
            },
            "h4": {
              "font-weight": "500",
              "margin-bottom": "0",
              "text-align": "left"
            },
            "p": {
              "color": "#767676",
              "text-align": "left"
            },
            ".card-wrapper": {
              "position": "relative",
              "box-shadow": "0px 0px 0px 0px rgba(0, 0, 0, 0)",
              "transition": "box-shadow 0.3s",
              "&:hover": {
                "box-shadow": "0px 0px 30px 0px rgba(0, 0, 0, 0.05)",
                "transition": "box-shadow 0.3s"
              }
            },
            ".card-img": {
              "position": "absolute",
              "top": "0",
              "left": "0",
              "width": "100%",
              "overflow": "hidden"
            }
          },
          "_name": "features4",
          "_customHTML": "<section class=\"features4\" group=\"Features\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n    \n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"0\">\n        \n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"color\" title=\"Cards Bg\" name=\"cardsBg\" value=\"#ffffff\">\n        <select title=\"Cards\" name=\"cardsAmount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\" selected>3</option>\n            <option value=\"4\">4</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background5.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#f9f295\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#cebfaf\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>     \n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container\">\n        <div class=\"media-container-row\" mbr-cards=\"bootstrap\">\n            <div class=\"card p-3 col-12 col-md-6\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-wrapper media-container-row media-container-row\">\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title\">\n                            Emitir</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Pulsos de luz necesarios para captar la información de la zona de piel del paciente a evaluar.</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"card p-3 col-12 col-md-6 col-12 col-md-6\" mbr-if=\"cardsAmount > 1\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-wrapper media-container-row\">\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title\">\n                            Transformar</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Las ondas fotoacústicas recibidas en impulsos eléctricos, para después ser convertidos en datos e imágenes fotoacústicas.</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"card p-3 col-12 col-md-6\" mbr-if=\"cardsAmount > 2\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-wrapper media-container-row\">\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title\">\n                            Almacenar</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            La información para que el paciente y el médico tengan registro de la situación del tejido a lo largo del tiempo.</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"card p-3 col-12 col-md-6\" mbr-if=\"cardsAmount > 3\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-wrapper media-container-row\">\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title\">\n                            Unlimited Sites\n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Mobirise gives you the freedom to develop as many websites as you like given the fact that it is a desktop app.\n                        </p>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFfRFg5d2A",
          "_anchor": "features4-1e",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".card-box": {
              "background-color": "@cardsBg",
              "padding": "2rem"
            },
            "h4": {
              "font-weight": "500",
              "margin-bottom": "0",
              "text-align": "left"
            },
            "p": {
              "color": "#767676",
              "text-align": "left"
            },
            ".card-wrapper": {
              "position": "relative",
              "box-shadow": "0px 0px 0px 0px rgba(0, 0, 0, 0)",
              "transition": "box-shadow 0.3s",
              "&:hover": {
                "box-shadow": "0px 0px 30px 0px rgba(0, 0, 0, 0.05)",
                "transition": "box-shadow 0.3s"
              }
            },
            ".card-img": {
              "position": "absolute",
              "top": "0",
              "left": "0",
              "width": "100%",
              "overflow": "hidden"
            }
          },
          "_name": "features4",
          "_customHTML": "<section class=\"features4\" group=\"Features\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n    \n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"1\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n        \n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"color\" title=\"Cards Bg\" name=\"cardsBg\" value=\"#ffffff\">\n        <select title=\"Cards\" name=\"cardsAmount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\" selected>3</option>\n            <option value=\"4\">4</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background5.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#f9f295\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#cebfaf\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>     \n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container\">\n        <div class=\"media-container-row\" mbr-cards=\"bootstrap\">\n            <div class=\"card p-3 col-12 col-md-6\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-wrapper media-container-row media-container-row\">\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title\">\n                            Registrar</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">Los datos relacionados a la profundidad del tejido necroso y mostrarlos a manera de datos y de imágenes.</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"card p-3 col-12 col-md-6 col-12 col-md-6\" mbr-if=\"cardsAmount > 1\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-wrapper media-container-row\">\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title\">\n                            Comparar</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            La información e imágenes obtenidas con valores estándar preestablecidos.</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"card p-3 col-12 col-md-6\" mbr-if=\"cardsAmount > 2\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-wrapper media-container-row\">\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title\">\n                            Controlar</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            La información recabada mediante el procesador interno para el adecuado funcionamiento del dispositivo.</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"card p-3 col-12 col-md-6\" mbr-if=\"cardsAmount > 3\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-wrapper media-container-row\">\n                    <div class=\"card-box\">\n                        <h4 class=\"card-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title\">\n                            Unlimited Sites\n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Mobirise gives you the freedom to develop as many websites as you like given the fact that it is a desktop app.\n                        </p>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFfRFSUHTx",
          "_anchor": "features4-1f",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' &amp;&amp; bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline=\"\" title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline=\"\" title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"0\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\" checked=\"\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax=\"\">\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax=\"\">\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected=\"\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked=\"\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n        <input type=\"range\" inline=\"\" title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay &amp;&amp; bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    FULL WIDTH INTRO\n                </h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Tabla de requerimientos</h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Full width intro with adjustable height, background image and a color overlay. Click any text to edit or style it.\n                </p>\n                <div mbr-buttons=\"\" mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">LEARN MORE</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_anchor": "header16-1i",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "rFfUje2094",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "color": "#767676"
            },
            ".container-table": {
              "margin": "0 auto"
            },
            ".scroll": {
              "overflow-x": "auto",
              "padding": "0"
            },
            ".dataTables_wrapper": {
              "display": "block",
              ".search": {
                "margin-bottom": ".5rem"
              },
              ".table": {
                "overflow-x": "auto"
              }
            },
            "table": {
              "width": "100% !important",
              "margin-top": "6px",
              "border": "1px solid @tbColor",
              "margin-bottom": "0",
              "th": {
                "border-top": "none",
                "transition": "all .2s",
                "border-bottom": "none",
                "&:hover": {
                  "background": "@tbColor",
                  "color": "contrast(@tbColor)"
                }
              },
              "td": {
                "border-top": "1px solid @tbColor"
              },
              "&.table": {
                "& when (@tbBackground)": {
                  "background": "@tbBgColor"
                }
              }
            },
            ".dataTables_filter": {
              "text-align": "right",
              "margin-bottom": ".5rem",
              "label": {
                "display": "inline",
                "white-space": "normal !important"
              },
              "input": {
                "display": "inline",
                "width": "auto",
                "margin-left": ".5rem",
                "border-radius": "100px",
                "padding-left": "1rem"
              }
            },
            ".dataTables_info": {
              "padding-bottom": "1rem",
              "padding-top": "1rem",
              "white-space": "normal !important"
            },
            "@media (max-width: 992px)": {
              ".dataTables_filter": {
                "text-align": "center"
              }
            },
            "@media (max-width: 350px)": {
              ".dataTables_filter": {
                "text-align": "center",
                "input": {
                  "width": "100% !important",
                  "margin-left": "0 !important"
                }
              }
            }
          },
          "_name": "table1",
          "_customHTML": "<section class=\"section-table\" group=\"Tables\" plugins=\"dataTables\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n  <mbr-parameters>\n  <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"0\">\n    <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n    <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n    <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n    <input type=\"range\" inline title=\"Columns\" name=\"tableColumns\" min=\"1\" max=\"50\" step=\"1\" value=\"6\">\n    <input type=\"range\" inline title=\"Rows\" name=\"tableRows\" min=\"1\" max=\"50\" step=\"1\" value=\"11\">\n    <input type=\"color\" title=\"Table Border Color\" name=\"tbColor\" value=\"#cccccc\">\n    <input type=\"checkbox\" title=\"Table Background\" name=\"tbBackground\" checked>\n    <input type=\"color\" title=\"Table Background Color\" name=\"tbBgColor\" value=\"#ffffff\" condition=\"tbBackground\">\n    <input type=\"checkbox\" title=\"Search\" name=\"isSearch\">\n    <fieldset type=\"background\" name=\"bg\" parallax>\n      <input type=\"image\" title=\"Background Image\" value=\"../_images/background1.jpg\" parallax>\n      <input type=\"color\" title=\"Background Color\" value=\"#f9f9f9\" selected>\n      <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n    </fieldset>\n    <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n    <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#ffffff\" condition=\"overlay && bg.type !== 'color'\">\n    <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.9\" condition=\"overlay && bg.type !== 'color'\">\n  <!-- End block parameters -->\n  </mbr-parameters>\n  <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n  </div>\n  <div class=\"container container-table\">\n      <h2 class=\"mbr-section-title mbr-fonts-style align-center pb-3\" mbr-theme-style=\"display-2\" data-app-selector=\".mbr-section-title\" mbr-if=\"showTitle\">\n          Table\n      </h2>\n      <h3 class=\"mbr-section-subtitle mbr-fonts-style align-center pb-5 mbr-light\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\"><br>Se evaluaron los conceptos analizados bajo una serie de criterios (1 es el menor puntaje posible y 4 es el mayor)</h3>\n      <div class=\"table-wrapper\">\n        <div class=\"container\">\n          <div class=\"row search\" mbr-if=\"isSearch\">\n            <div class=\"col-md-6\"></div>\n            <div class=\"col-md-6\">\n                <div class=\"dataTables_filter\">\n                  <label mbr-text class=\"searchInfo mbr-fonts-style\" mbr-theme-style=\"display-7\">Search:</label>\n                  <input class=\"form-control input-sm\" disabled>\n                </div>\n            </div>\n          </div>\n        </div>\n\n        <div class=\"container scroll\">\n          <table class=\"table\" mbr-class=\"{'isSearch':isSearch}\" cellspacing=\"0\">\n            <thead>\n              <tr class=\"table-heads \" mbr-list mbr-list-grow=\"tableColumns\">\n                  <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\"></th>\n                  <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\">\n                      CONCEPTO 1</th>\n                  <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\">\n                      CONCEPTO 2</th>\n                  <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\">\n                      CONCEPTO 3</th>\n              <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\">\n                      CONCEPTO 4</th><th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\">\n                      CONCEPTO 5</th></tr>\n            </thead>\n\n            <tbody mbr-list mbr-list-grow=\"tableRows\">\n              <tr mbr-list mbr-list-grow=\"tableColumns\"> \n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>FACILIDAD DE ENSAMBLAJE</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td></tr>\n              <tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>COSTO DE TECNOLOGÍA</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td></tr>\n              <tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>COSTO DE OPERACIÓN</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td></tr>\n              <tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>SEGURIDAD</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td></tr>\n            <tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>ESTABILIDAD</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td></tr><tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>TAMAÑO</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td></tr><tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>FACILIDAD DE MANEJO</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td></tr><tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>PESO</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td></tr><tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>INTENSIDAD DE LUZ</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">4</td></tr><tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>MANTENIMIENTO</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">3</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">2</td></tr><tr mbr-list mbr-list-grow=\"tableColumns\">\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>TOTAL</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>31</b></td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">28</td>\n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">30</td>\n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">30</td><td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">27</td></tr></tbody>\n          </table>\n        </div>\n        <div class=\"container table-info-container\">\n          <div class=\"row info\" mbr-if=\"isSearch\">\n            <div class=\"col-md-6\">\n              <div class=\"dataTables_info mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <span mbr-text class=\"infoBefore\" data-app-selector=\".dataTables_info\"></span>\n                <span class=\"inactive infoRows\"></span>\n                <span mbr-text class=\"infoAfter\" data-app-selector=\".dataTables_info\"></span>\n                <span mbr-text class=\"infoFilteredBefore\" data-app-selector=\".dataTables_info\"></span>\n                <span class=\"inactive infoRows\"></span>\n                <span mbr-text class=\"infoFilteredAfter\" data-app-selector=\".dataTables_info\"></span>\n              </div>\n            </div>\n            <div class=\"col-md-6\"></div>\n          </div>\n        </div>\n      </div>\n    </div>\n</section>",
          "_cid": "rFfUDsmi4l",
          "_anchor": "table1-1j",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "h2": {
              "text-align": "left"
            },
            "h4": {
              "text-align": "left",
              "font-weight": "500"
            },
            "p": {
              "color": "#767676",
              "text-align": "left"
            },
            ".aside-content": {
              "flex-basis": "100%",
              "-webkit-flex-basis": "100%"
            },
            ".block-content": {
              "display": "-webkit-flex",
              "flex-direction": "column",
              "-webkit-flex-direction": "column",
              "word-break": "break-word"
            },
            ".media": {
              "margin": "initial",
              "align-items": "center",
              "-webkit-align-items": "center"
            },
            ".mbr-figure": {
              "align-self": "flex-start",
              "-webkit-align-self": "flex-start",
              "-webkit-flex-shrink": "0",
              "flex-shrink": "0"
            },
            ".card-img": {
              "padding-right": "2rem",
              "width": "auto"
            },
            ".card-img span": {
              "font-size": "72px",
              "color": "#707070"
            },
            "@media (min-width: 992px)": {
              ".mbr-figure": {
                "padding-right": "4rem",
                "& when (@reverseContent)": {
                  "padding-right": "0",
                  "padding-left": "4rem"
                }
              },
              ".media-container-row": {
                "& when (@reverseContent)": {
                  "-webkit-flex-direction": "row-reverse"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".mbr-figure": {
                "padding-right": "0",
                "padding-bottom": "1rem",
                "margin-bottom": "2rem",
                "& when (@reverseContent)": {
                  "padding-bottom": "0",
                  "margin-bottom": "0",
                  "padding-top": "1rem",
                  "margin-top": "2rem"
                }
              },
              ".media-container-row": {
                "& when (@reverseContent)": {
                  "-webkit-flex-direction": "column-reverse"
                }
              }
            },
            "@media (max-width: 300px)": {
              ".card-img span": {
                "font-size": "40px !important"
              }
            },
            "P": {
              "color": "#232323"
            }
          },
          "_name": "features11",
          "_customHTML": "<section class=\"features11\" group=\"Features\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\">\n        <input type=\"checkbox\" title=\"Show Text Header\" name=\"showTextHead\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Icons\" name=\"showIcons\">\n        <input type=\"checkbox\" title=\"Media on Left/Right\" name=\"reverseContent\">\n        <input type=\"range\" inline title=\"Media Size\" name=\"mediaSize\" min=\"20\" max=\"80\" step=\"5\" value=\"50\">\n        <select title=\"Cards\" name=\"cardsAmount\">\n            <option value=\"1\" selected>1</option>\n            <option value=\"2\">2</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background5.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#ffffff\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">   \n        <div class=\"col-md-12\">\n            <div class=\"media-container-row\">\n                <div class=\"mbr-figure m-auto\" mbr-style=\"{'width': mediaSize + '%'}\">\n                    <img src=\"@PROJECT_PATH@/assets/images/matriz-438x523.png\" alt=\"Mobirise\" title>\n                </div>\n                <div class=\" align-left aside-content\">\n                    <h2 class=\"mbr-title pt-2 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\">Matriz Morfológica<br></h2>\n                    <div class=\"mbr-section-text\">\n                        <p class=\"mbr-text mb-5 pt-3 mbr-light mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-text\">\n                        Click any text or icon to edit or style it. Use the block parameters to hide/show text or icons and change media size or position.\n                        </p>\n                    </div>\n\n                    <div class=\"block-content\" mbr-if=\"showTextHead||showText||showIcons\">\n                        <div class=\"card p-3 pr-3\">\n                            <div class=\"media\">\n                                <div class=\" align-self-center card-img pb-3\" mbr-if=\"showIcons\">\n                                    <span mbr-icon class=\"mbri-extension mbr-iconfont\"></span>\n                                </div>     \n                                <div class=\"media-body\">\n                                    <h4 class=\"card-title mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTextHead\">\n                                        Over 400 Amazing Blocks\n                                    </h4>\n                                </div>\n                            </div>                \n\n                            <div class=\"card-box\">\n                                <p class=\"block-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">ALTERNATIVA DE SOLUCIÓN 1<br>- Láser de neodimio<br>- Sensor de ultrasonido HC-SR04<br>- Teléfono móvil<br>- Arduino nano<br>ALTERNATIVA DE SOLUCIÓN 2<br>- Diodo láser<br>- Sensor de ultrasonido HC-SR04<br>- Teléfono móvil<br>- Arduino nano<br>ALTERNATIVA DE SOLUCIÓN 3<br>- Diodo láser<br>- Transductor de limpieza por ultrasonido CN2538-63LB<br>- Teléfono móvil<br>- Arduino mini<br>ALTERNATIVA DE SOLUCIÓN 4&nbsp;<br>- Láser de neodimio<br>-&nbsp;Transductor de limpieza por ultrasonido CN2538-63LB<br>- Teléfono móvil<br>- Arduino mini<br>ALTERNATIVA DE SOLUCIÓN 5<br>- Láser de rubí<br>- Transductor pequeño de ultrasonido CN6830-38LA<br>- Teléfono móvil<br>- Arduino Micro</p>\n                            </div>\n                        </div>\n\n                        <div class=\"card p-3 pr-3\" mbr-if=\"cardsAmount > 1\">\n                            <div class=\"media\">\n                                <div class=\"align-self-center card-img pb-3\" mbr-if=\"showIcons\">\n                                    <span mbr-icon class=\"mbri-drag-n-drop2 mbr-iconfont\"></span>\n                                </div>     \n                                <div class=\"media-body\">\n                                    <h4 class=\"card-title mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTextHead\">\n                                        Easy and Simple to Use\n                                    </h4>\n                                </div>\n                            </div>                \n\n                            <div class=\"card-box\">\n                                <p class=\"block-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                                    Cut down the development time with drag-and-drop website builder. Drop the blocks into the page, edit content inline and publish - no technical skills required.\n                                </p>\n                            </div>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div> \n    </div>          \n</section>",
          "_cid": "rFu8rDIeXD",
          "_anchor": "features11-1q",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "color": "#767676",
              "font-weight": "300"
            },
            ".media-container-row": {
              "word-wrap": "break-word",
              "word-break": "break-word",
              "align-items": "stretch",
              "-webkit-align-items": "stretch"
            },
            ".card_cont": {
              "-o-transition": "all .5s",
              "-ms-transition": "all .5s",
              "-moz-transition": "all .5s",
              "-webkit-transition": "all .5s",
              "transition": "all .5s",
              "-o-backface-visibility": "hidden",
              "-ms-backface-visibility": "hidden",
              "-moz-backface-visibility": "hidden",
              "-webkit-backface-visibility": "hidden",
              "backface-visibility": "hidden",
              "position": "absolute",
              "top": "0px",
              "left": "0px",
              "text-align": "center",
              "background-color": "#eee"
            },
            ".card-front": {
              "z-index": "2",
              "padding": "0",
              "width": "100%",
              "height": "100%",
              "overflow": "hidden",
              "img": {
                "height": "100%",
                "min-width": "100%",
                "width": "auto"
              }
            },
            ".card_back": {
              "width": "100%",
              "height": "100%",
              "padding": "30px 30px",
              "color": "#ffffff",
              "background-color": "@crdBckColor",
              "z-index": "1",
              "margin": "0",
              "text-align": "center",
              "overflow": "hidden",
              "& when (@animation = 'horizontal')": {
                "-o-transform": "rotateY(-180deg)",
                "-ms-transform": "rotateY(-180deg)",
                "-moz-transform": "rotateY(-180deg)",
                "-webkit-transform": "rotateY(-180deg)",
                "transform": "rotateY(-180deg)"
              },
              "& when (@animation = 'vertical')": {
                "-o-transform": "rotateX(-180deg)",
                "-ms-transform": "rotateX(-180deg)",
                "-moz-transform": "rotateX(-180deg)",
                "-webkit-transform": "rotateX(-180deg)",
                "transform": "rotateX(-180deg)"
              }
            },
            ".card": {
              "min-height": "300px"
            },
            ".card:hover": {
              ".card-front": {
                "z-index": "1",
                "& when (@animation = 'horizontal')": {
                  "-o-transform": "rotateY(180deg)",
                  "-ms-transform": "rotateY(180deg)",
                  "-moz-transform": "rotateY(180deg)",
                  "-webkit-transform": "rotateY(180deg)",
                  "transform": "rotateY(180deg)"
                },
                "& when (@animation = 'vertical')": {
                  "-o-transform": "rotateX(180deg)",
                  "-ms-transform": "rotateX(180deg)",
                  "-moz-transform": "rotateX(180deg)",
                  "-webkit-transform": "rotateX(180deg)",
                  "transform": "rotateX(180deg)"
                }
              },
              ".card_back": {
                "z-index": "2",
                "& when (@animation = 'horizontal')": {
                  "-o-transform": "rotateY(0deg)",
                  "-ms-transform": "rotateY(0deg)",
                  "-moz-transform": "rotateY(0deg)",
                  "-webkit-transform": "rotateY(0deg)",
                  "transform": "rotateY(0deg)"
                },
                "& when (@animation = 'vertical')": {
                  "-o-transform": "rotateX(0deg)",
                  "-ms-transform": "rotateX(0deg)",
                  "-moz-transform": "rotateX(0deg)",
                  "-webkit-transform": "rotateX(0deg)",
                  "transform": "rotateX(0deg)"
                }
              }
            },
            ".builderCard": {
              ".card_back": {
                "border-bottom-left-radius": "100px"
              },
              ".card_cont": {
                "-o-backface-visibility": "hidden",
                "-ms-backface-visibility": "hidd",
                "-moz-backface-visibility": "visible",
                "-webkit-backface-visibility": "visible",
                "backface-visibility": "visible"
              }
            },
            "P": {
              "color": "#232323"
            },
            "H4": {
              "color": "#232323"
            }
          },
          "_name": "features15",
          "_customHTML": "<section class=\"features15\" group=\"Animated Features\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\" plugins=\"mbr-flip-card\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitles\" name=\"showSubtitle\">\n        <input type=\"checkbox\" title=\"Show Block Titles\" name=\"showTitles\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n\n        <input type=\"color\" title=\"Card Back Color\" name=\"crdBckColor\" value=\"#f7ed4a\"> \n        <select title=\"Animation\" name=\"animation\">\n            <option value=\"horizontal\" selected>Horizontal</option>\n            <option value=\"vertical\">Vertical</option>\n        </select>\n\n        <select title=\"Cards\" name=\"cardsAmount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\" selected>2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background5.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#ffffff\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.7\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container\">\n        <h2 class=\"mbr-section-title pb-3 align-center mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title\">Conceptos de la propuesta de solución</h2>\n        <h3 class=\"mbr-section-subtitle display-5 align-center mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\"></h3>\n\n        <div class=\"media-container-row container pt-5 mt-2\" mbr-cards=\"bootstrap\">\n\n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\">\n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"@PROJECT_PATH@/assets/images/mamadisimo1-795x441.png\" alt=\"Mobirise\" title>\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title display-5 py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">Distribución de los datos obtenidos por señales fotoacústicas</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Se genera una tabla donde se ordenan los datos de concentración y profundidad del tejido muerto según las partes del cuerpo, se comparan según una base de datos estándar, y luego se general las conclusiones del análisis.</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\" mbr-if=\"cardsAmount > 1\">\n                \n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"@PROJECT_PATH@/assets/images/captura1-489x511.png\" alt=\"Mobirise\" title>\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">Funcionamiento</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Concepto preliminar de cómo se vería el dispositivo conectado a un teléfono móvil<br><br></p>\n                    </div>\n                </div>\n            </div>\n            \n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\" mbr-if=\"cardsAmount > 2\">\n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"../_images/background3.jpg\" alt=\"Mobirise\">\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">\n                            Unlimited Sites\n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Mobirise gives you the freedom to develop as many websites as you like given the fact that it is a desktop app.\n                        </p>\n                    </div>\n                </div> \n            </div>\n\n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\" mbr-if=\"cardsAmount > 3\">\n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"../_images/background4.jpg\" alt=\"Mobirise\">\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">\n                            Host Anywhere \n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Publish your website to a local drive, FTP or host on Amazon S3, Google Cloud, Github Pages. Don't be a hostage to just one platform or service provider.\n                        </p>\n                    </div>\n                </div> \n            </div>\n        </div>\n</div></section>",
          "_cid": "rFSKKKwF1m",
          "_anchor": "features15-1w",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "color": "#767676",
              "font-weight": "300"
            },
            ".media-container-row": {
              "word-wrap": "break-word",
              "word-break": "break-word",
              "align-items": "stretch",
              "-webkit-align-items": "stretch"
            },
            ".card_cont": {
              "-o-transition": "all .5s",
              "-ms-transition": "all .5s",
              "-moz-transition": "all .5s",
              "-webkit-transition": "all .5s",
              "transition": "all .5s",
              "-o-backface-visibility": "hidden",
              "-ms-backface-visibility": "hidden",
              "-moz-backface-visibility": "hidden",
              "-webkit-backface-visibility": "hidden",
              "backface-visibility": "hidden",
              "position": "absolute",
              "top": "0px",
              "left": "0px",
              "text-align": "center",
              "background-color": "#eee"
            },
            ".card-front": {
              "z-index": "2",
              "padding": "0",
              "width": "100%",
              "height": "100%",
              "overflow": "hidden",
              "img": {
                "height": "100%",
                "min-width": "100%",
                "width": "auto"
              }
            },
            ".card_back": {
              "width": "100%",
              "height": "100%",
              "padding": "30px 30px",
              "color": "#ffffff",
              "background-color": "@crdBckColor",
              "z-index": "1",
              "margin": "0",
              "text-align": "center",
              "overflow": "hidden",
              "& when (@animation = 'horizontal')": {
                "-o-transform": "rotateY(-180deg)",
                "-ms-transform": "rotateY(-180deg)",
                "-moz-transform": "rotateY(-180deg)",
                "-webkit-transform": "rotateY(-180deg)",
                "transform": "rotateY(-180deg)"
              },
              "& when (@animation = 'vertical')": {
                "-o-transform": "rotateX(-180deg)",
                "-ms-transform": "rotateX(-180deg)",
                "-moz-transform": "rotateX(-180deg)",
                "-webkit-transform": "rotateX(-180deg)",
                "transform": "rotateX(-180deg)"
              }
            },
            ".card": {
              "min-height": "300px"
            },
            ".card:hover": {
              ".card-front": {
                "z-index": "1",
                "& when (@animation = 'horizontal')": {
                  "-o-transform": "rotateY(180deg)",
                  "-ms-transform": "rotateY(180deg)",
                  "-moz-transform": "rotateY(180deg)",
                  "-webkit-transform": "rotateY(180deg)",
                  "transform": "rotateY(180deg)"
                },
                "& when (@animation = 'vertical')": {
                  "-o-transform": "rotateX(180deg)",
                  "-ms-transform": "rotateX(180deg)",
                  "-moz-transform": "rotateX(180deg)",
                  "-webkit-transform": "rotateX(180deg)",
                  "transform": "rotateX(180deg)"
                }
              },
              ".card_back": {
                "z-index": "2",
                "& when (@animation = 'horizontal')": {
                  "-o-transform": "rotateY(0deg)",
                  "-ms-transform": "rotateY(0deg)",
                  "-moz-transform": "rotateY(0deg)",
                  "-webkit-transform": "rotateY(0deg)",
                  "transform": "rotateY(0deg)"
                },
                "& when (@animation = 'vertical')": {
                  "-o-transform": "rotateX(0deg)",
                  "-ms-transform": "rotateX(0deg)",
                  "-moz-transform": "rotateX(0deg)",
                  "-webkit-transform": "rotateX(0deg)",
                  "transform": "rotateX(0deg)"
                }
              }
            },
            ".builderCard": {
              ".card_back": {
                "border-bottom-left-radius": "100px"
              },
              ".card_cont": {
                "-o-backface-visibility": "hidden",
                "-ms-backface-visibility": "hidd",
                "-moz-backface-visibility": "visible",
                "-webkit-backface-visibility": "visible",
                "backface-visibility": "visible"
              }
            },
            "P": {
              "color": "#232323"
            },
            "H4": {
              "color": "#232323"
            }
          },
          "_name": "features15",
          "_customHTML": "<section class=\"features15\" group=\"Animated Features\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\" plugins=\"mbr-flip-card\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitles\" name=\"showSubtitle\">\n        <input type=\"checkbox\" title=\"Show Block Titles\" name=\"showTitles\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n\n        <input type=\"color\" title=\"Card Back Color\" name=\"crdBckColor\" value=\"#f7ed4a\"> \n        <select title=\"Animation\" name=\"animation\">\n            <option value=\"horizontal\" selected>Horizontal</option>\n            <option value=\"vertical\">Vertical</option>\n        </select>\n\n        <select title=\"Cards\" name=\"cardsAmount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\" selected>2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background5.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#ffffff\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.7\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container\">\n        <h2 class=\"mbr-section-title pb-3 align-center mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title\">Matriz de Evaluación</h2>\n        <h3 class=\"mbr-section-subtitle display-5 align-center mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\">\n            Click on the bottom left corner of the card to change the front image. In browser this corner will not be shown.\n        </h3>\n\n        <div class=\"media-container-row container pt-5 mt-2\" mbr-cards=\"bootstrap\">\n\n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\">\n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"@PROJECT_PATH@/assets/images/procesos1-1052x579.png\" alt=\"Mobirise\" title>\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title display-5 py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">Comparación técnica</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">Mediante estándares y criterios previamente determinados se dispuso a comparar dos proyectos preliminares,y determinar cuál de ellos se asemeja más a la propuesta de solución ya ideada.</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\" mbr-if=\"cardsAmount > 1\">\n                \n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"@PROJECT_PATH@/assets/images/procesos2-1-954x511.png\" alt=\"Mobirise\" title>\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">Comparación económia</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">Mediante ciertos estándares y criterios se dispuso a comparar dos proyectos preliminares segun diferentes impactos económicos,y determinar cuál de ellos se asemeja más a la propuesta de solución ya ideada.</p>\n                    </div>\n                </div>\n            </div>\n            \n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\" mbr-if=\"cardsAmount > 2\">\n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"../_images/background3.jpg\" alt=\"Mobirise\">\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">\n                            Unlimited Sites\n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Mobirise gives you the freedom to develop as many websites as you like given the fact that it is a desktop app.\n                        </p>\n                    </div>\n                </div> \n            </div>\n\n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\" mbr-if=\"cardsAmount > 3\">\n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"../_images/background4.jpg\" alt=\"Mobirise\">\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">\n                            Host Anywhere \n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Publish your website to a local drive, FTP or host on Amazon S3, Google Cloud, Github Pages. Don't be a hostage to just one platform or service provider.\n                        </p>\n                    </div>\n                </div> \n            </div>\n        </div>\n</div></section>",
          "_cid": "rFum2jyJDf",
          "_anchor": "features15-1t",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "color": "#767676",
              "font-weight": "300"
            },
            ".media-container-row": {
              "word-wrap": "break-word",
              "word-break": "break-word",
              "align-items": "stretch",
              "-webkit-align-items": "stretch"
            },
            ".card_cont": {
              "-o-transition": "all .5s",
              "-ms-transition": "all .5s",
              "-moz-transition": "all .5s",
              "-webkit-transition": "all .5s",
              "transition": "all .5s",
              "-o-backface-visibility": "hidden",
              "-ms-backface-visibility": "hidden",
              "-moz-backface-visibility": "hidden",
              "-webkit-backface-visibility": "hidden",
              "backface-visibility": "hidden",
              "position": "absolute",
              "top": "0px",
              "left": "0px",
              "text-align": "center",
              "background-color": "#eee"
            },
            ".card-front": {
              "z-index": "2",
              "padding": "0",
              "width": "100%",
              "height": "100%",
              "overflow": "hidden",
              "img": {
                "height": "100%",
                "min-width": "100%",
                "width": "auto"
              }
            },
            ".card_back": {
              "width": "100%",
              "height": "100%",
              "padding": "30px 30px",
              "color": "#ffffff",
              "background-color": "@crdBckColor",
              "z-index": "1",
              "margin": "0",
              "text-align": "center",
              "overflow": "hidden",
              "& when (@animation = 'horizontal')": {
                "-o-transform": "rotateY(-180deg)",
                "-ms-transform": "rotateY(-180deg)",
                "-moz-transform": "rotateY(-180deg)",
                "-webkit-transform": "rotateY(-180deg)",
                "transform": "rotateY(-180deg)"
              },
              "& when (@animation = 'vertical')": {
                "-o-transform": "rotateX(-180deg)",
                "-ms-transform": "rotateX(-180deg)",
                "-moz-transform": "rotateX(-180deg)",
                "-webkit-transform": "rotateX(-180deg)",
                "transform": "rotateX(-180deg)"
              }
            },
            ".card": {
              "min-height": "300px"
            },
            ".card:hover": {
              ".card-front": {
                "z-index": "1",
                "& when (@animation = 'horizontal')": {
                  "-o-transform": "rotateY(180deg)",
                  "-ms-transform": "rotateY(180deg)",
                  "-moz-transform": "rotateY(180deg)",
                  "-webkit-transform": "rotateY(180deg)",
                  "transform": "rotateY(180deg)"
                },
                "& when (@animation = 'vertical')": {
                  "-o-transform": "rotateX(180deg)",
                  "-ms-transform": "rotateX(180deg)",
                  "-moz-transform": "rotateX(180deg)",
                  "-webkit-transform": "rotateX(180deg)",
                  "transform": "rotateX(180deg)"
                }
              },
              ".card_back": {
                "z-index": "2",
                "& when (@animation = 'horizontal')": {
                  "-o-transform": "rotateY(0deg)",
                  "-ms-transform": "rotateY(0deg)",
                  "-moz-transform": "rotateY(0deg)",
                  "-webkit-transform": "rotateY(0deg)",
                  "transform": "rotateY(0deg)"
                },
                "& when (@animation = 'vertical')": {
                  "-o-transform": "rotateX(0deg)",
                  "-ms-transform": "rotateX(0deg)",
                  "-moz-transform": "rotateX(0deg)",
                  "-webkit-transform": "rotateX(0deg)",
                  "transform": "rotateX(0deg)"
                }
              }
            },
            ".builderCard": {
              ".card_back": {
                "border-bottom-left-radius": "100px"
              },
              ".card_cont": {
                "-o-backface-visibility": "hidden",
                "-ms-backface-visibility": "hidd",
                "-moz-backface-visibility": "visible",
                "-webkit-backface-visibility": "visible",
                "backface-visibility": "visible"
              }
            },
            "H4": {
              "color": "#232323"
            },
            "P": {
              "color": "#232323"
            }
          },
          "_name": "features15",
          "_customHTML": "<section class=\"features15\" group=\"Animated Features\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\" plugins=\"mbr-flip-card\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitles\" name=\"showSubtitle\">\n        <input type=\"checkbox\" title=\"Show Block Titles\" name=\"showTitles\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n\n        <input type=\"color\" title=\"Card Back Color\" name=\"crdBckColor\" value=\"#f7ed4a\"> \n        <select title=\"Animation\" name=\"animation\">\n            <option value=\"horizontal\" selected>Horizontal</option>\n            <option value=\"vertical\">Vertical</option>\n        </select>\n\n        <select title=\"Cards\" name=\"cardsAmount\">\n            <option value=\"1\" selected>1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background5.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#ffffff\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.7\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container\">\n        <h2 class=\"mbr-section-title pb-3 align-center mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title\">\n            Proyecto óptimo</h2>\n        <h3 class=\"mbr-section-subtitle display-5 align-center mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\">\n            Click on the bottom left corner of the card to change the front image. In browser this corner will not be shown.\n        </h3>\n\n        <div class=\"media-container-row container pt-5 mt-2\" mbr-cards=\"bootstrap\">\n\n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\">\n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"@PROJECT_PATH@/assets/images/procesos3-2-921x506.png\" alt=\"Mobirise\" title>\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title display-5 py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">Comparación con proyecto ideal</h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">Se comparan las dos propuestas con el proyecto ideal mediante un gráfico <i><b>valor técnico - valor económico</b></i>, secciones que serán vistas &nbsp;en sus respectivas tablas con más detalles. &nbsp;</p>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\" mbr-if=\"cardsAmount > 1\">\n                \n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"../_images/background2.jpg\" alt=\"Mobirise\">\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">\n                            Easy and Simple to Use\n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Drop the blocks into the page, edit content inline and publish - no technical skills required.\n                        </p>\n                    </div>\n                </div>\n            </div>\n            \n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\" mbr-if=\"cardsAmount > 2\">\n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"../_images/background3.jpg\" alt=\"Mobirise\">\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">\n                            Unlimited Sites\n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Mobirise gives you the freedom to develop as many websites as you like given the fact that it is a desktop app.\n                        </p>\n                    </div>\n                </div> \n            </div>\n\n            <div class=\"col-12 col-md-6 mb-4\" mbr-class=\"{'col-lg-4': cardsAmount == '3','col-lg-3': cardsAmount == '4'}\" mbr-if=\"cardsAmount > 3\">\n                <div class=\"card flip-card p-5 align-center\">\n                    <div class=\"card-front card_cont\">\n                        <img src=\"../_images/background4.jpg\" alt=\"Mobirise\">\n                    </div>\n                    <div class=\"card_back card_cont\">\n                        <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitles\">\n                            Host Anywhere \n                        </h4>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                            Publish your website to a local drive, FTP or host on Amazon S3, Google Cloud, Github Pages. Don't be a hostage to just one platform or service provider.\n                        </p>\n                    </div>\n                </div> \n            </div>\n        </div>\n</div></section>",
          "_cid": "rFSFXBJXb4",
          "_anchor": "features15-1v",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            ".content": {
              "@media (max-width: 767px)": {
                "text-align": "center",
                "> div:not(:last-child)": {
                  "margin-bottom": "2rem"
                }
              }
            },
            ".media-wrap": {
              "@media (max-width: 767px)": {
                "margin-bottom": "1rem"
              },
              ".mbr-iconfont-logo": {
                "font-size": "7.5rem",
                "color": "#f36"
              },
              "img": {
                "height": "6rem"
              }
            },
            ".footer-lower": {
              ".copyright": {
                "@media (max-width: 767px)": {
                  "margin-bottom": "1rem",
                  "text-align": "center"
                }
              },
              "hr": {
                "margin": "1rem 0",
                "border-color": "#fff",
                "opacity": ".05"
              },
              ".social-list": {
                "padding-left": "0",
                "margin-bottom": "0",
                "list-style": "none",
                "display": "flex",
                "flex-wrap": "wrap",
                "justify-content": "flex-end",
                "-webkit-justify-content": "flex-end",
                ".mbr-iconfont-social": {
                  "font-size": "1.3rem",
                  "color": "#fff"
                },
                ".soc-item": {
                  "margin": "0 .5rem"
                },
                "a": {
                  "margin": "0",
                  "opacity": ".5",
                  "-webkit-transition": ".2s linear",
                  "transition": ".2s linear",
                  "&:hover": {
                    "opacity": "1"
                  }
                },
                "@media (max-width: 767px)": {
                  "justify-content": "center",
                  "-webkit-justify-content": "center"
                }
              }
            }
          },
          "_name": "footer1",
          "_customHTML": "<section group=\"Footers\" mbr-class=\"{'mbr-reveal': reveal, 'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->  \n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"checkbox\" title=\"Show Copyright\" name=\"showCopyright\" checked>\n        <select title=\"Icons\" name=\"iconsCount\">\n            <option value=\"0\" selected>0</option>\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\">6</option>\n        </select>\n        <input type=\"checkbox\" title=\"Reveal effect\" name=\"reveal\">\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#2e2e2e\" selected>\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#3C3C3C\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row content text-white\">\n            <div class=\"col-12 col-md-3\">\n                <div class=\"media-wrap\">\n                    <a href=\"https://mobirise.com/\">\n                        <img src=\"@PROJECT_PATH@/assets/images/icono-192x192.png\" alt=\"Mobirise\" title>\n                    </a>\n                </div>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">&nbsp; &nbsp;</h5>\n                <p class=\"mbr-text\">&nbsp; &nbsp;</p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Contáctanos</h5>\n                <p class=\"mbr-text\">\n                    Email: pibgrupo5@gmail.com&nbsp;<br><br><br></p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\"><p>&nbsp;<br></p></h5>\n                <p class=\"mbr-text\">&nbsp;&nbsp;</p>\n            </div>\n        </div>\n        <div class=\"footer-lower\" mbr-if=\"showCopyright\">\n            <div class=\"media-container-row\">\n                <div class=\"col-sm-12\">\n                    <hr>\n                </div>\n            </div>\n            <div class=\"media-container-row mbr-white\">\n                <div class=\"col-sm-6 copyright\">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".copyright > p\">\n                        © Copyright 2017 Mobirise - All Rights Reserved\n                    </p>\n                </div>\n                <div class=\"col-md-6\">\n                    <div class=\"social-list align-right\" mbr-if=\"iconsCount > 0\">\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>0\">\n                            <a href=\"https://twitter.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"mbr-iconfont mbr-iconfont-social socicon-googleplus socicon\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>1\">\n                            <a href=\"https://www.facebook.com/pages/Mobirise/1616226671953247\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-facebook socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>2\">\n                            <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-youtube socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>3\">\n                            <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-instagram socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>4\">\n                            <a href=\"https://plus.google.com/u/0/+Mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-googleplus socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>5\">\n                            <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-behance socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_anchor": "footer1-17",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "rFfPfhayzI",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "page5.html": {
      "settings": {
        "meta_descr": "Site Generator Description",
        "title": "Problema",
        "order": 2
      },
      "components": [
        {
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "-webkit-flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".navbar-expand": {
                "flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#333333\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"gpi5.html\">\n                         <img src=\"@PROJECT_PATH@/assets/images/icono-1-192x192.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\" title>\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"gpi5.html\" data-app-placeholder=\"Type Text\">Grupo 5</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\"><li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.com\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">\n                        </a>\n                </li>\n                <li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page5.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Problema</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page2.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Usuario</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page3.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Estado del Arte</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page4.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">La Propuesta</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page1.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Entregables</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page6.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Bibliografía</a></li></ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\"><a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a></div>\n        </div>\n    </nav>\n</section>",
          "_cid": "qTkzRZLJNu",
          "_anchor": "menu1-f",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "h1": {
              "color": "#616161"
            },
            "h2, h3, p": {
              "color": "#767676"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic"
            },
            "H1": {
              "color": "#232323"
            },
            ".mbr-text, .mbr-section-btn": {
              "color": "#232323"
            }
          },
          "_name": "header9",
          "_customHTML": "<section class=\"header9\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n\n        <input type=\"checkbox\" name=\"halfSize\" title=\"Half Size\" checked>\n        <select title=\"Align\" name=\"alignHalf\" condition=\"halfSize\">\n            <option value=\"1\" selected>Left</option>\n            <option value=\"2\">Center</option>\n            <option value=\"3\">Right</option>\n        </select>\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/web1-2-1100x734.jpeg\" selected parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#ffffff\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.4\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"media-container-column mbr-white\" mbr-class=\"{'col-lg-8 col-md-10': halfSize, 'm-auto': halfSize &&  alignHalf==2, 'ml-auto': halfSize &&  alignHalf==3}\">\n            <h1 class=\"mbr-section-title align-left mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">DIABETES MELLITUS</h1>\n            <h3 class=\"mbr-section-subtitle align-left mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                Beautiful mobile websites\n            </h3>\n            <p class=\"mbr-text align-left pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                La diabetes es una enfermedad crónica que aparece cuando el páncreas no produce insulina suficiente o cuando el organismo no utiliza eficazmente la insulina que produce. El efecto de la diabetes no controlada es la hiperglucemia (aumento del azúcar en la sangre). (OMS, s.f.)</p>\n            <div class=\"mbr-section-btn align-left\" mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\">\n                <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.co\">LEARN MORE</a>\n                <a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\">LIVE DEMO</a>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "rFaLjXqfMU",
          "_anchor": "header9-h",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "color": "#767676",
              "text-align": "center",
              "font-weight": "300"
            },
            ".timeline-text-content": {
              "padding": "2rem 2.5rem",
              "background": "@timelineColor",
              "margin-left": "2rem",
              "p": {
                "margin-bottom": "0"
              }
            },
            ".time-line-date-content": {
              "margin-right": "2rem",
              "p": {
                "padding": "2rem 2.5rem",
                "background": "@timelineColor",
                "float": "right"
              }
            },
            ".timeline-element": {
              "margin-bottom": "50px",
              "position": "relative",
              "word-wrap": "break-word",
              "word-break": "break-word",
              "display": "-webkit-flex",
              "flex-direction": "row",
              "-webkit-flex-direction": "row",
              "&:hover": {
                ".mbr-timeline-date": {
                  "box-shadow": "0 7px 20px 0px rgba(0, 0, 0, 0.08)",
                  "transition": "all .4s"
                },
                ".timeline-text-content": {
                  "box-shadow": "0 7px 20px 0px rgba(0, 0, 0, 0.08)",
                  "transition": "all .4s"
                }
              }
            },
            ".mbr-timeline-date, .timeline-text-content": {
              "transition": "all .4s"
            },
            ".reverse": {
              "flex-direction": "row-reverse",
              "-webkit-flex-direction": "row-reverse",
              ".timeline-text-content": {
                "margin-right": "2rem",
                "margin-left": "0"
              },
              ".time-line-date-content": {
                "margin-left": "2rem",
                "margin-right": "0rem",
                "p": {
                  "float": "left"
                }
              }
            },
            ".iconBackground": {
              "position": "absolute",
              "left": "50%",
              "width": "20px",
              "height": "20px",
              "line-height": "30px",
              "text-align": "center",
              "border-radius": "50%",
              "font-size": "30px",
              "display": "inline-block",
              "background-color": "@timelineColor",
              "top": "20px",
              "margin-left": "-10px"
            },
            ".separline:before": {
              "top": "20px",
              "bottom": "0",
              "position": "absolute",
              "content": "\"\"",
              "width": "2px",
              "background-color": "@timelineColor",
              "left": "calc(50% ~\"-\" 1px)",
              "height": "calc(100% ~\"+\" 4rem)"
            },
            "@media (max-width: 768px)": {
              ".iconBackground": {
                "left": "0 !important"
              },
              ".separline:before": {
                "left": "0!important"
              },
              ".timeline-text-content": {
                "margin-left": "0 !important"
              },
              ".time-line-date-content": {
                "margin-right": "0 !important",
                "p": {
                  "float": "left !important"
                }
              },
              ".reverse": {
                ".time-line-date-content": {
                  "margin-left": "0 !important"
                },
                ".timeline-text-content": {
                  "margin-right": "0 !important"
                }
              }
            },
            ".reverseTimeline": {
              "display": "flex",
              "flex-direction": "column-reverse"
            }
          },
          "_name": "timeline1",
          "_customHTML": "<section class=\"timeline1\" group=\"Timelines & Steps\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel)-->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n        \n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show Dates\" name=\"showDates\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n        \n        <input type=\"color\" title=\"Timelines Color\" name=\"timelineColor\" value=\"#b2ccd2\">\n        <select title=\"Timelines count\" name=\"timelinesAmount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\" selected>6</option>\n            <option value=\"7\">7</option>\n            <option value=\"8\">8</option>\n            <option value=\"9\">9</option>\n            <option value=\"10\">10</option>\n            <option value=\"11\">11</option>\n            <option value=\"12\">12</option>\n        </select>\n        <input type=\"checkbox\" title=\"Reverse Timeline\" name=\"reverseTimeline\">\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#efefef\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#cccccc\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.9\" condition=\"overlay && bg.type !== 'color'\">\n        <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container align-center\">\n        <h2 class=\"mbr-section-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title\">\n            Efectos</h2>\n        <h3 class=\"mbr-section-subtitle pb-5 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\">\n            Los principales efectos de la diabetes son:</h3>\n\n        <div class=\"container timelines-container\" mbri-timelines mbr-class=\"{'reverseTimeline' : reverseTimeline}\">\n            <!--1-->\n            <div class=\"row timeline-element reverse\" mbr-class=\"{'separline': !reverseTimeline &amp;&amp; timelinesAmount > 1}\">\n                 <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">         \n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                            1 january 2018  \n                        </p>\n                    </div>\n                </div>\n           <span class=\"iconBackground\"></span>\n            <div class=\"col-xs-12 col-md-6 align-right\">\n                <div class=\"timeline-text-content\">\n                    <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">Neuropatía diabética</h4>\n                    <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">Los nervios, principalmente de las extremidades, tienden a perder sensibilidad. Esto ocasiona que estas partes corporales estén expuestas a recibir daños sin que el paciente lo note&nbsp;</p>\n                 </div>\n            </div>\n            </div>\n            <!--2-->\n            <div class=\"row timeline-element \" mbr-if=\"timelinesAmount>1\" mbr-class=\"{'separline':timelinesAmount>2 &amp;&amp; !reverseTimeline || !reverseTimeline &amp;&amp; timelinesAmount > 2 || reverseTimeline &amp;&amp; timelinesAmount > 1}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                            2 february 2019  \n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">Pie diabético</h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Infección de los tejidos profundos de la piel a partir de múltiples heridas causadas por la neuropatía en los pies del paciente</p>\n                    </div>\n                </div>\n            </div>\n            <!--3-->\n            <div class=\"row timeline-element reverse\" mbr-if=\"timelinesAmount>2\" mbr-class=\"{'separline': !reverseTimeline &amp;&amp; timelinesAmount > 3 || reverseTimeline &amp;&amp; timelinesAmount > 2}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                            3 march 2020\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-right\">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">Amputación</h4>      \n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Una neuropatía mal controlada puede desembocar en la aparición de gangrena o tejido necroso. Una cantidad de este ocasiona que la extremidad \"muera\" y tenga que ser amputada por el bien del paciente.&nbsp;</p>\n                    </div>\n                </div>\n            </div>\n            <!--4-->\n            <div class=\"row timeline-element \" mbr-if=\"timelinesAmount>3\" mbr-class=\"{'separline': !reverseTimeline &amp;&amp; timelinesAmount > 4 || reverseTimeline &amp;&amp; timelinesAmount > 3}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                            4 april 2021\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">Úlceras</h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">La úlcera del pie diabético es una llaga o herida abierta que en general se produce en la planta del pie en aproximadamente el 15% de los pacientes con diabetes. Un 6% de los diabéticos que presentan una úlcera en el pie deben ser hospitalizados debido a una infección u otra complicación relacionada con la úlcera.</p>\n                    </div>\n                </div>\n            </div>\n            <!--5-->\n            <div class=\"row timeline-element reverse\" mbr-if=\"timelinesAmount>4\" mbr-class=\"{'separline': !reverseTimeline &amp;&amp; timelinesAmount > 5 || reverseTimeline &amp;&amp; timelinesAmount > 4}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                            5 may 2022\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-right\">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">Cardiopatías</h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            La obstrucción de los vasos sanguíneos debido al severo incremento de glucosa en la sangre puede incrementar el riesgo de que surgan cardiopatías o enfermedades al corzón en el paciente.</p>\n                    </div>\n                </div>\n            </div>\n            <!--6-->\n            <div class=\"row timeline-element\" mbr-if=\"timelinesAmount>5\" mbr-class=\"{'separline': !reverseTimeline &amp;&amp; timelinesAmount > 6 || reverseTimeline &amp;&amp; timelinesAmount > 5}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                       <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                            6 june 2023\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">Reamputación</h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">Tras la amputación, un mal cuiado puede se causa de la aparición de nuevas úlceras. A su vez, estas cusarán que aparezca nuevo tejido necroso, el cual puede causar que el paciente vuelva a ser amputado.&nbsp;</p>\n                    </div>\n                </div>\n            </div>\n            <!--7-->\n            <div class=\"row timeline-element reverse\" mbr-if=\"timelinesAmount>6\" mbr-class=\"{'separline': !reverseTimeline &amp;&amp; timelinesAmount > 7 || reverseTimeline &amp;&amp; timelinesAmount > 6}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                           7 july 2024\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-right\">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Responsive Design\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n            <!--8-->\n            <div class=\"row timeline-element\" mbr-if=\"timelinesAmount>7\" mbr-class=\"{'separline': !reverseTimeline &amp;&amp; timelinesAmount > 8 || reverseTimeline &amp;&amp; timelinesAmount > 7}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                           8 august 2025  \n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Smart Watch\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n            <!--9-->\n            <div class=\"row timeline-element reverse\" mbr-if=\"timelinesAmount>8\" mbr-class=\"{'separline': !reverseTimeline &amp;&amp; timelinesAmount > 9 || reverseTimeline &amp;&amp; timelinesAmount > 8}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                           9 september 2026\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-right\">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Design out of the box\n                        </h4>\n\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n            <!--10-->\n            <div class=\"row timeline-element\" mbr-if=\"timelinesAmount>9\" mbr-class=\"{'separline': !reverseTimeline &amp;&amp; timelinesAmount > 10 || reverseTimeline &amp;&amp; timelinesAmount > 9}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                       <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                          10 october 2027\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Awesome Reports\n                        </h4> \n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n            <!--11-->\n            <div class=\"row timeline-element reverse\" mbr-if=\"timelinesAmount>10\" mbr-class=\"{'separline': !reverseTimeline &amp;&amp; timelinesAmount > 11 || reverseTimeline &amp;&amp; timelinesAmount > 10}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6  align-left\">\n                    <div class=\"time-line-date-content\">\n                       <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                          11 november 2028\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-right\">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Design out of the box\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n            <!--12-->\n            <div class=\"row timeline-element\" mbr-if=\"timelinesAmount>11\" mbr-class=\"{'separline': reverseTimeline &amp;&amp; timelinesAmount > 11}\">\n                <div class=\"timeline-date-panel col-xs-12 col-md-6 align-right\">\n                    <div class=\"time-line-date-content\">\n                        <p class=\"mbr-timeline-date mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showDates\" data-app-selector=\".mbr-timeline-date\">\n                           12 december 2029\n                        </p>\n                    </div>\n                </div>\n                <span class=\"iconBackground\"></span>\n                <div class=\"col-xs-12 col-md-6 align-left \">\n                    <div class=\"timeline-text-content\">\n                        <h4 class=\"mbr-timeline-title pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-timeline-title\">\n                            Awesome Reports\n                        </h4>\n                        <p class=\"mbr-timeline-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-timeline-text\">\n                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam erat libero, bibendum in libero tempor, luctus volutpat ligula. Integer fringilla porttitor pretium. Nam erat felis, iaculis id justo ut, ullamcorper feugiat elit. Proin vel lectus auctor, porttitor ligula vitae, convallis leo. In eget massa elit.\n                        </p>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFaLWBpYEd",
          "_anchor": "timeline1-j",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "h3": {
              "text-align": "center",
              "font-weight": "300"
            },
            ".wrap": {
              "width": "150px",
              "height": "150px",
              "margin": "0 auto"
            },
            ".mbr-section-subtitle": {
              "color": "#767676"
            },
            ".card": {
              "-webkit-flex-basis": "100%",
              "flex-basis": "100%",
              "word-wrap": "break-word"
            },
            "ellipse": {
              "stroke": "rgba(206, 206, 206, 0.4)"
            },
            "path": {
              "stroke": "@progressColor"
            },
            "@media (max-width: 991px) and (min-width: 768px)": {
              ".card": {
                "-webkit-flex-basis": "33%",
                "flex-basis": "33%"
              }
            }
          },
          "_name": "progress-bars3",
          "_customHTML": "<section class=\"progress-bars3\" group=\"Progress\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" plugins=\"as-pie-progress\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n \n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) --> \n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n       \n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"color\" title=\"Progress Color\" name=\"progressColor\" value=\"#149dcc\">\n\n        <select title=\"Progress count\" name=\"progressCount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\" selected>3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\">6</option>\n        </select>\n        <input type=\"range\" inline title=\"Progress 1\" name=\"progress1\" min=\"0\" max=\"100\" step=\"1\" value=\"60\">\n        <input type=\"range\" inline title=\"Progress 2\" name=\"progress2\" min=\"0\" max=\"100\" step=\"1\" value=\"8\" condition=\"progressCount>1\">\n        <input type=\"range\" inline title=\"Progress 3\" name=\"progress3\" min=\"0\" max=\"100\" step=\"1\" value=\"6\" condition=\"progressCount>2\">\n        <input type=\"range\" inline title=\"Progress 4\" name=\"progress4\" min=\"0\" max=\"100\" step=\"1\" value=\"80\" condition=\"progressCount>3\">\n        <input type=\"range\" inline title=\"Progress 5\" name=\"progress5\" min=\"0\" max=\"100\" step=\"1\" value=\"90\" condition=\"progressCount>4\">\n        <input type=\"range\" inline title=\"Progress 6\" name=\"progress6\" min=\"0\" max=\"100\" step=\"1\" value=\"100\" condition=\"progressCount>5\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background1.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#ffffff\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.7\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters> \n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    \n    <div class=\"container\">\n        <h2 class=\"mbr-section-title pb-3 align-center mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title\">Medición del efecto</h2>\n\n        <h3 class=\"mbr-section-subtitle mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\">\n            Al año 2018:</h3>\n    \n        <div class=\"media-container-row pt-5 mt-2\">\n            <div class=\"card p-3 align-center\">\n                <div class=\"wrap\">\n                    <div class=\"pie_progress progress1\" role=\"progressbar\" data-goal=\"{{progress1}}\">\n                        <p class=\"pie_progress__number mbr-fonts-style\" mbr-theme-style=\"display-5\">60%</p>\n                    </div>\n                </div> \n                <div class=\"mbr-crt-title pt-3\">\n                    <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitle\">El 60% de diabéticos tiene riesgo de desarrollar neuropatía</h4>\n                </div>                 \n            </div>\n\n            <div class=\"card p-3 align-center\" mbr-if=\"progressCount>1\">\n                <div class=\"wrap\">\n                    <div class=\"pie_progress progress2\" role=\"progressbar\" data-goal=\"{{progress2}}\">\n                        <p class=\"pie_progress__number mbr-fonts-style\" mbr-theme-style=\"display-5\">8%</p>\n                    </div>\n                </div> \n                <div class=\"mbr-crt-title pt-3\">\n                    <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitle\">\n                        Prevalencia de diabetes en Lima (745 600 aproximadamente)</h4>\n                </div>                 \n            </div>\n\n            <div class=\"card p-3 align-center\" mbr-if=\"progressCount>2\">\n                <div class=\"wrap\">\n                    <div class=\"pie_progress progress3\" role=\"progressbar\" data-goal=\"{{progress3}}\">\n                        <p class=\"pie_progress__number mbr-fonts-style\" mbr-theme-style=\"display-5\">7%</p>\n                    </div>\n                </div> \n                <div class=\"mbr-crt-title pt-3\">\n                    <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitle\">7 de cada 100 personas mayores de 25 padecen diabetes a nivel nacional</h4>\n                </div>                 \n            </div>\n\n            <div class=\"card p-3 align-center\" mbr-if=\"progressCount>3\">\n                <div class=\"wrap\">\n                    <div class=\"pie_progress progress4\" role=\"progressbar\" data-goal=\"{{progress4}}\">\n                        <p class=\"pie_progress__number mbr-fonts-style\" mbr-theme-style=\"display-5\"></p>\n                    </div>\n                </div> \n                <div class=\"mbr-crt-title pt-3\">\n                    <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitle\">\n                        Safety\n                    </h4>\n                </div>                 \n            </div>\n\n            <div class=\"card p-3 align-center\" mbr-if=\"progressCount>4\">\n                <div class=\"wrap\">\n                    <div class=\"pie_progress progress5\" role=\"progressbar\" data-goal=\"{{progress5}}\">\n                        <p class=\"pie_progress__number mbr-fonts-style\" mbr-theme-style=\"display-5\"></p>\n                    </div>\n                </div> \n                <div class=\"mbr-crt-title pt-3\">\n                    <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitle\">\n                        Study\n                    </h4>\n                </div>                 \n            </div>\n\n            <div class=\"card p-3 align-center\" mbr-if=\"progressCount>5\">\n                <div class=\"wrap\">\n                    <div class=\"pie_progress progress6\" role=\"progressbar\" data-goal=\"{{progress6}}\">\n                        <p class=\"pie_progress__number mbr-fonts-style\" mbr-theme-style=\"display-5\"></p>\n                    </div>\n                </div> \n                <div class=\"mbr-crt-title pt-3\">\n                    <h4 class=\"card-title py-2 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showTitle\">\n                        Gifts\n                    </h4>\n                </div>                 \n            </div>\n        </div>\n</div></section>",
          "_cid": "rFaLDi4irS",
          "_anchor": "progress-bars3-i",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".progress": {
              "width": "100%"
            },
            "progress": {
              "height": "8px"
            },
            "h3": {
              "text-align": "center",
              "font-weight": "300"
            },
            ".mbr-section-subtitle": {
              "color": "#767676"
            },
            ".progress_value": {
              "position": "relative"
            },
            ".progress_elements": {
              "margin": "0 auto"
            },
            ".title-wrap": {
              "display": "flex",
              "justify-content": "space-between",
              "-webkit-justify-content": "space-between"
            },
            ".progress1 .progressbar-number:before, .progress2 .progressbar-number:before, .progress3 .progressbar-number:before, .progress4 .progressbar-number:before": {
              "position": "absolute",
              "right": "15px",
              "top": "0"
            },
            "progress[value]::-webkit-progress-bar": {
              "background": "rgba(206, 206, 206, 0.4)"
            },
            "progress::-webkit-progress-value": {
              "background": "@progressColor"
            },
            "progress[value]::-moz-progress-bar": {
              "background": "@progressColor"
            },
            "progress::-ms-fill": {
              "background": "@progressColor"
            },
            ".progress1 .progressbar-number:before": {
              "content": "'@{progress1}'"
            },
            ".progress2 .progressbar-number:before": {
              "content": "'@{progress2}'"
            },
            ".progress3 .progressbar-number:before": {
              "content": "'@{progress3}'"
            },
            ".progress4 .progressbar-number:before": {
              "content": "'@{progress4}'"
            },
            ".progress-primary": {
              "background": "rgba(206, 206, 206, 0.4)",
              "border": "none",
              "outline": "none"
            },
            ".progress-primary::-webkit-progress-bar": {
              "background": "rgba(206, 206, 206, 0.4)"
            },
            ".progress_value span": {
              "padding-left": "30px"
            }
          },
          "_name": "progress-bars1",
          "_customHTML": "<section class=\"progress-bars1\" group=\"Progress\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n    \n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->  \n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"4\">        \n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"color\" title=\"Progress Color\" name=\"progressColor\" value=\"#149dcc\">\n\n        <select title=\"Progress count\" name=\"progressCount\">\n             <option value=\"1\">1</option>\n             <option value=\"2\">2</option>\n             <option value=\"3\">3</option>\n             <option value=\"4\" selected>4</option>\n        </select>\n\n        <input type=\"range\" inline title=\"Progress 1\" name=\"progress1\" min=\"0\" max=\"100\" step=\"1\" value=\"2\">\n        <input type=\"range\" inline title=\"Progress 2\" name=\"progress2\" min=\"0\" max=\"100\" step=\"1\" value=\"8\" condition=\"progressCount>1\">\n        <input type=\"range\" inline title=\"Progress 3\" name=\"progress3\" min=\"0\" max=\"100\" step=\"1\" value=\"10\" condition=\"progressCount>2\">\n        <input type=\"range\" inline title=\"Progress 4\" name=\"progress4\" min=\"0\" max=\"100\" step=\"1\" value=\"28\" condition=\"progressCount>3\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background1.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#ffffff\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.7\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->  \n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <h2 class=\"mbr-section-title pb-2 align-center mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title\">\n            Comparación con estándares</h2>\n\n        <h3 class=\"mbr-section-subtitle pb-5 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\">\n            Índice de prevalencia con respecto a otros países</h3>\n\n        <div class=\"progress_elements\">\n            <div class=\"progress1 pb-5\">\n                <div class=\"title-wrap\">\n                    <div class=\"progressbar-title mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                        <p data-app-selector=\".progressbar-title p, .progress_value\">Zimbabwe (segunda menor prevalencia a nivel mundial - 2017)</p>\n                    </div>\n                    <div class=\"progress_value mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                        <div class=\"progressbar-number\"></div>\n                        <span>%</span>\n                    </div>\n                </div>\n                <progress class=\"progress progress-primary\" value=\"{{progress1}}\" max=\"100\">\n                </progress>\n            </div>\n            \n            <div class=\"progress2 pb-5\" mbr-if=\"progressCount > 1\">\n                <div class=\"title-wrap\">\n                    <div class=\"progressbar-title mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                        <p data-app-selector=\".progressbar-title p, .progress_value\">\n                           Perú (2018)</p>\n                    </div>\n                <div class=\"progress_value mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                    <div class=\"progressbar-number\"></div>\n                    <span>%</span>\n                </div>\n                </div>\n                <progress class=\"progress progress-primary\" value=\"{{progress2}}\" max=\"100\">\n                </progress>\n            </div>\n            \n            <div class=\"progress3 pb-5\" mbr-if=\"progressCount > 2\">\n                <div class=\"title-wrap\">\n                    <div class=\"progressbar-title mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                        <p data-app-selector=\".progressbar-title p, .progress_value\">Chile (2017)</p>\n                    </div>\n                    <div class=\"progress_value mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                        <div class=\"progressbar-number\"></div>\n                        <span>%</span>\n                    </div>\n                </div>\n                <progress class=\"progress progress-primary\" value=\"{{progress3}}\" max=\"100\">\n                </progress>\n            </div>\n            \n            <div class=\"progress4\" mbr-if=\"progressCount > 3\">\n                <div class=\"title-wrap\">\n                    <div class=\"progressbar-title mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                        <p data-app-selector=\".progressbar-title p, .progress_value\">\n                            Tuvalu (Mayor prevalencia a nivel mundial - 2017)</p>\n                    </div>\n                <div class=\"progress_value mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                    <div class=\"progressbar-number\"></div>\n                    <span>%</span>\n                </div>\n                </div>\n                <progress class=\"progress progress-primary\" value=\"{{progress4}}\" max=\"100\">\n                </progress>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFaULChQD8",
          "_anchor": "progress-bars1-k",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "color": "#767676"
            },
            ".container-table": {
              "margin": "0 auto"
            },
            ".scroll": {
              "overflow-x": "auto",
              "padding": "0"
            },
            ".dataTables_wrapper": {
              "display": "block",
              ".search": {
                "margin-bottom": ".5rem"
              },
              ".table": {
                "overflow-x": "auto"
              }
            },
            "table": {
              "width": "100% !important",
              "margin-top": "6px",
              "border": "1px solid @tbColor",
              "margin-bottom": "0",
              "th": {
                "border-top": "none",
                "transition": "all .2s",
                "border-bottom": "none",
                "&:hover": {
                  "background": "@tbColor",
                  "color": "contrast(@tbColor)"
                }
              },
              "td": {
                "border-top": "1px solid @tbColor"
              },
              "&.table": {
                "& when (@tbBackground)": {
                  "background": "@tbBgColor"
                }
              }
            },
            ".dataTables_filter": {
              "text-align": "right",
              "margin-bottom": ".5rem",
              "label": {
                "display": "inline",
                "white-space": "normal !important"
              },
              "input": {
                "display": "inline",
                "width": "auto",
                "margin-left": ".5rem",
                "border-radius": "100px",
                "padding-left": "1rem"
              }
            },
            ".dataTables_info": {
              "padding-bottom": "1rem",
              "padding-top": "1rem",
              "white-space": "normal !important"
            },
            "@media (max-width: 992px)": {
              ".dataTables_filter": {
                "text-align": "center"
              }
            },
            "@media (max-width: 350px)": {
              ".dataTables_filter": {
                "text-align": "center",
                "input": {
                  "width": "100% !important",
                  "margin-left": "0 !important"
                }
              }
            }
          },
          "_name": "table1",
          "_customHTML": "<section class=\"section-table\" group=\"Tables\" plugins=\"dataTables\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n  <mbr-parameters>\n  <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n    <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\">\n    <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n    <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n    <input type=\"range\" inline title=\"Columns\" name=\"tableColumns\" min=\"1\" max=\"50\" step=\"1\" value=\"2\">\n    <input type=\"range\" inline title=\"Rows\" name=\"tableRows\" min=\"1\" max=\"50\" step=\"1\" value=\"2\">\n    <input type=\"color\" title=\"Table Border Color\" name=\"tbColor\" value=\"#cccccc\">\n    <input type=\"checkbox\" title=\"Table Background\" name=\"tbBackground\" checked>\n    <input type=\"color\" title=\"Table Background Color\" name=\"tbBgColor\" value=\"#ffffff\" condition=\"tbBackground\">\n    <input type=\"checkbox\" title=\"Search\" name=\"isSearch\">\n    <fieldset type=\"background\" name=\"bg\" parallax>\n      <input type=\"image\" title=\"Background Image\" value=\"../_images/background1.jpg\" parallax>\n      <input type=\"color\" title=\"Background Color\" value=\"#f9f9f9\" selected>\n      <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n    </fieldset>\n    <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n    <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#ffffff\" condition=\"overlay && bg.type !== 'color'\">\n    <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.9\" condition=\"overlay && bg.type !== 'color'\">\n  <!-- End block parameters -->\n  </mbr-parameters>\n  <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n  </div>\n  <div class=\"container container-table\">\n      <h2 class=\"mbr-section-title mbr-fonts-style align-center pb-3\" mbr-theme-style=\"display-2\" data-app-selector=\".mbr-section-title\" mbr-if=\"showTitle\">\n          Impacto económico</h2>\n      <h3 class=\"mbr-section-subtitle mbr-fonts-style align-center pb-5 mbr-light\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\">\n            Para el paciente y para el Estado (Perú21, 2018)</h3>\n      <div class=\"table-wrapper\">\n        <div class=\"container\">\n          <div class=\"row search\" mbr-if=\"isSearch\">\n            <div class=\"col-md-6\"></div>\n            <div class=\"col-md-6\">\n                <div class=\"dataTables_filter\">\n                  <label mbr-text class=\"searchInfo mbr-fonts-style\" mbr-theme-style=\"display-7\">Search:</label>\n                  <input class=\"form-control input-sm\" disabled>\n                </div>\n            </div>\n          </div>\n        </div>\n\n        <div class=\"container scroll\">\n          <table class=\"table\" mbr-class=\"{'isSearch':isSearch}\" cellspacing=\"0\">\n            <thead>\n              <tr class=\"table-heads \" mbr-list mbr-list-grow=\"tableColumns\">\n                  <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\"></th>\n                  \n                  \n                  \n              <th mbr-text class=\"head-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".head-item\">Gasto del Estado (soles)</th></tr>\n            </thead>\n\n            <tbody mbr-list mbr-list-grow=\"tableRows\">\n              <tr mbr-list mbr-list-grow=\"tableColumns\"> \n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>Paciente controlado</b></td>\n                \n                \n                \n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">1392</td></tr>\n              \n              \n              \n            <tr mbr-list mbr-list-grow=\"tableColumns\"> \n                <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\"><b>Paciente no controlado</b></td>\n                \n                \n                \n              <td mbr-text class=\"body-item mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".body-item\">19661</td></tr></tbody>\n          </table>\n        </div>\n        <div class=\"container table-info-container\">\n          <div class=\"row info\" mbr-if=\"isSearch\">\n            <div class=\"col-md-6\">\n              <div class=\"dataTables_info mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <span mbr-text class=\"infoBefore\" data-app-selector=\".dataTables_info\">Showing</span>\n                <span class=\"inactive infoRows\"></span>\n                <span mbr-text class=\"infoAfter\" data-app-selector=\".dataTables_info\">entries</span>\n                <span mbr-text class=\"infoFilteredBefore\" data-app-selector=\".dataTables_info\">(filtered from</span>\n                <span class=\"inactive infoRows\"></span>\n                <span mbr-text class=\"infoFilteredAfter\" data-app-selector=\".dataTables_info\"> total entries)</span>\n              </div>\n            </div>\n            <div class=\"col-md-6\"></div>\n          </div>\n        </div>\n      </div>\n    </div>\n</section>",
          "_cid": "rFaYQmkeNV",
          "_anchor": "table1-l",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            ".content": {
              "@media (max-width: 767px)": {
                "text-align": "center",
                "> div:not(:last-child)": {
                  "margin-bottom": "2rem"
                }
              }
            },
            ".media-wrap": {
              "@media (max-width: 767px)": {
                "margin-bottom": "1rem"
              },
              ".mbr-iconfont-logo": {
                "font-size": "7.5rem",
                "color": "#f36"
              },
              "img": {
                "height": "6rem"
              }
            },
            ".footer-lower": {
              ".copyright": {
                "@media (max-width: 767px)": {
                  "margin-bottom": "1rem",
                  "text-align": "center"
                }
              },
              "hr": {
                "margin": "1rem 0",
                "border-color": "#fff",
                "opacity": ".05"
              },
              ".social-list": {
                "padding-left": "0",
                "margin-bottom": "0",
                "list-style": "none",
                "display": "flex",
                "flex-wrap": "wrap",
                "justify-content": "flex-end",
                "-webkit-justify-content": "flex-end",
                ".mbr-iconfont-social": {
                  "font-size": "1.3rem",
                  "color": "#fff"
                },
                ".soc-item": {
                  "margin": "0 .5rem"
                },
                "a": {
                  "margin": "0",
                  "opacity": ".5",
                  "-webkit-transition": ".2s linear",
                  "transition": ".2s linear",
                  "&:hover": {
                    "opacity": "1"
                  }
                },
                "@media (max-width: 767px)": {
                  "justify-content": "center",
                  "-webkit-justify-content": "center"
                }
              }
            }
          },
          "_name": "footer1",
          "_customHTML": "<section group=\"Footers\" mbr-class=\"{'mbr-reveal': reveal, 'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->  \n        <input type=\"range\" inline=\"\" title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline=\"\" title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"checkbox\" title=\"Show Copyright\" name=\"showCopyright\" checked=\"\">\n        <select title=\"Icons\" name=\"iconsCount\">\n            <option value=\"0\" selected=\"\">0</option>\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\">6</option>\n        </select>\n        <input type=\"checkbox\" title=\"Reveal effect\" name=\"reveal\">\n        <fieldset type=\"background\" name=\"bg\" parallax=\"\">\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#2e2e2e\" selected=\"\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked=\"\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#3C3C3C\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n        <input type=\"range\" inline=\"\" title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay &amp;&amp; bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay &amp;&amp; bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row content text-white\">\n            <div class=\"col-12 col-md-3\">\n                <div class=\"media-wrap\">\n                    <a href=\"https://mobirise.com/\">\n                        <img src=\"@PROJECT_PATH@/assets/images/icono-192x192.png\" alt=\"Mobirise\" title=\"\">\n                    </a>\n                </div>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">&nbsp; &nbsp;</h5>\n                <p class=\"mbr-text\">&nbsp; &nbsp;</p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Contáctanos</h5>\n                <p class=\"mbr-text\">\n                    Email: pibgrupo5@gmail.com&nbsp;<br><br><br></p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\"><p>&nbsp;<br></p></h5>\n                <p class=\"mbr-text\">&nbsp;&nbsp;</p>\n            </div>\n        </div>\n        <div class=\"footer-lower\" mbr-if=\"showCopyright\">\n            <div class=\"media-container-row\">\n                <div class=\"col-sm-12\">\n                    <hr>\n                </div>\n            </div>\n            <div class=\"media-container-row mbr-white\">\n                <div class=\"col-sm-6 copyright\">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".copyright > p\">\n                        © Copyright 2017 Mobirise - All Rights Reserved\n                    </p>\n                </div>\n                <div class=\"col-md-6\">\n                    <div class=\"social-list align-right\" mbr-if=\"iconsCount > 0\">\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>0\">\n                            <a href=\"https://twitter.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"mbr-iconfont mbr-iconfont-social socicon-googleplus socicon\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>1\">\n                            <a href=\"https://www.facebook.com/pages/Mobirise/1616226671953247\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-facebook socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>2\">\n                            <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-youtube socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>3\">\n                            <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-instagram socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>4\">\n                            <a href=\"https://plus.google.com/u/0/+Mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-googleplus socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>5\">\n                            <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                                <span mbr-icon=\"\" class=\"socicon-behance socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_anchor": "footer1-14",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "rFfOCALUTI",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "page6.html": {
      "settings": {
        "meta_descr": "Website Generator Description",
        "title": "Bibliografía",
        "order": 7
      },
      "components": [
        {
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "-webkit-flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".navbar-expand": {
                "flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#333333\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"gpi5.html\">\n                         <img src=\"@PROJECT_PATH@/assets/images/icono-1-192x192.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\" title>\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"gpi5.html\" data-app-placeholder=\"Type Text\">Grupo 5</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\"><li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.com\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">\n                        </a>\n                </li>\n                <li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page5.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Problema</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page2.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Usuario</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page3.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Estado del Arte</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page4.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">La Propuesta</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page1.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Entregables</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page6.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Bibliografía</a></li></ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\"><a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a></div>\n        </div>\n    </nav>\n</section>",
          "_cid": "qTkzRZLJNu",
          "_anchor": "menu1-g",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#f7ed4a\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                    Repositorio bibliográfico</h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">\n                    Las referencias bibliográficas utilizadas en nuestro proyecto</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">LEARN MORE</a>\n                </div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "rFfPlKpuv3",
          "_anchor": "header16-19",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            ".counter-container": {
              "color": "#767676",
              "ul": {
                "margin-bottom": "0",
                "li": {
                  "margin-bottom": "1rem",
                  "& when (@stylizedCounters)": {
                    "list-style": "none",
                    "&:before": {
                      "position": "absolute",
                      "left": "0px",
                      "margin-top": "-10px",
                      "padding-top": "3px",
                      "content": "''",
                      "display": "inline-block",
                      "text-align": "center",
                      "margin": "5px 10px",
                      "line-height": "20px",
                      "transition": "all .2s",
                      "color": "contrast(@counterColor)",
                      "background": "@counterColor",
                      "width": "25px",
                      "height": "25px",
                      "border-radius": "50%",
                      "& when (@countersType = 'circle')": {
                        "background": "none",
                        "border": "1px solid @counterColor",
                        "color": "@counterColor"
                      },
                      "& when (@countersType = 'square')": {
                        "border-radius": "0"
                      },
                      "& when (@mark)": {
                        "content": "'✓'"
                      }
                    }
                  }
                }
              }
            }
          },
          "_name": "content12",
          "_customHTML": "<section class=\"mbr-section article content12\">\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"checkbox\" title=\"Stylized Counters\" name=\"stylizedCounters\" checked>\n        <input type=\"color\" title=\"Counter Color\" name=\"counterColor\" value=\"#149dcc\" condition=\"stylizedCounters\">\n        <input type=\"checkbox\" title=\"Stylized Counters\" name=\"stylizedCounters\" checked>\n        <input type=\"checkbox\" title=\"Mark\" name=\"mark\" checked condition=\"stylizedCounters\">\n        <select title=\"Counters Type\" name=\"countersType\" condition=\"stylizedCounters\">\n            <option value=\"default\" selected>Сircle Fill</option>\n            <option value=\"circle\">Circle</option>\n            <option value=\"square\">Square</option>\n        </select>   \n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#ffffff\">\n    <!-- End block parameters -->\n    </mbr-parameters> \n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"mbr-text counter-container col-12 col-md-8 mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\" data-multiline mbr-article>\n                <ul>\n                    <li><b>&nbsp;</b>Adlassnig, A: Mergen, W; Schnoll, W. (2006). Patente ES2330366T3: Telefono movil con un aparato de medida integrado. Recuperado de: <a href=\"https://patents.google.com/patent/ES2330366T3/es\">https://patents.google.com/patent/ES2330366T3/es</a></li><li>Álvarez Arredondo, I. (2018). “Día Mundial de la Diabetes: ¿cuánto gastan los peruanos para tratar la enfermedad?” Recuperado de: <a href=\"https://peru21-pe.cdn.ampproject.org/v/s/peru21.pe/economia/dia-mundial-diabetes-gastan-peruanos-tratar-enfermedad-nndc-440407-noticia/?outputType=amp&usqp=mq331AQEKAFwAQ%3D%3D&_js_v=0.1#aoh=15689147207406&referrer=https%3A%2F%2Fwww.google.com&_tf=De%20%251%24s&ampshare=https%3A%2F%2Fperu21.pe%2Feconomia%2Fdia-mundial-diabetes-gastan-peruanos-tratar-enfermedad-nndc-440407-noticia%2F\">https://peru21-pe.cdn.ampproject.org/v/s/peru21.pe/economia/dia-mundial-diabetes-gastan-peruanos-tratar-enfermedad-nndc-440407-noticia/?outputType=amp&amp;usqp=mq331AQEKAFwAQ%3D%3D&amp;amp_js_v=0.1#aoh=15689147207406&amp;referrer=https%3A%2F%2Fwww.google.com&amp;amp_tf=De%20%251%24s&amp;ampshare=https%3A%2F%2Fperu21.pe%2Feconomia%2Fdia-mundial-diabetes-gastan-peruanos-tratar-enfermedad-nndc-440407-noticia%2F</a></li><li>Centro Nacional de Epidemiología, Prevención y Control de Enfermedades – MINSA. (2019). Casos registrados de diabetes según grupo de edad y sexo, Perú 2018. Disponible en: <a href=\"https://www.dge.gob.pe/portal/docs/vigilancia/sala/2019/SE09/diabetes.pdf\">https://www.dge.gob.pe/portal/docs/vigilancia/sala/2019/SE09/diabetes.pdf</a></li><li>Centro Nacional de Epidemiología, Prevención y Control de Enfermedades – MINSA. (2019). Casos registrados de diabetes según sexo, Perú 2018. Disponible en: <a href=\"https://www.dge.gob.pe/portal/docs/vigilancia/sala/2019/SE09/diabetes.pdf\">https://www.dge.gob.pe/portal/docs/vigilancia/sala/2019/SE09/diabetes.pdf</a></li><li>Centro Nacional de Epidemiología, Prevención y Control de Enfermedades – MINSA. (2019).  Casos notificados de diabetes por nivel de atención de establecimiento, Perú 2018. Disponible en: <a href=\"https://www.dge.gob.pe/portal/docs/vigilancia/sala/2019/SE09/diabetes.pdf\">https://www.dge.gob.pe/portal/docs/vigilancia/sala/2019/SE09/diabetes.pdf</a></li><li>CIPHER HEALTHCARE,accedido el 27 de Octubre 2019 <a href=\"http://www.cipherhealthcare.com/\">http://www.cipherhealthcare.com/</a></li><li>Czuchnowski, J; Prevedel, R. (Traducción por E. López ). (2019). \"El efecto fotoacústico: ver a través del sonido\". Disponible en <a href=\"https://www.scienceinschool.org/es/content/el-efecto-fotoac%C3%BAstico-ver-trav%C3%A9s-del-sonido\">https://www.scienceinschool.org/es/content/el-efecto-fotoac%C3%BAstico-ver-trav%C3%A9s-del-sonido</a></li><li>Fundación Española del Corazón. (s.f.). Diabetes y riesgo cardiovascular. Recuperado de: <a href=\"https://fundaciondelcorazon.com/prevencion/riesgo-cardiovascular/diabetes.html\">https://fundaciondelcorazon.com/prevencion/riesgo-cardiovascular/diabetes.html</a></li><li>Estadísticas principales de la diabetes. (2019). Lima: Centro Nacional de Epidemiología, Prevención y Control de Enfermedades, p. 1-8. Disponible en: http://www.dge.gob.pe</li><li>-Federación Mexicana de Diabetes. (2015). “Impacto económico de la diabetes tipo 2 en América Latina”. Disponible en: http://fmdiabetes.org/impacto-economico-de-la-diabetes-tipo-2-en-america-latina/ &nbsp;</li><li>-International Diabetes Federation (IDF) Diabetes Atlas (8th ed.), International Diabetes Federation, Brussels, Belgium (2018)<br></li><li>-Ministerio de Salud. “Análisis de las causas de mortalidad en el Perú. 1986-2015.” (2018) [Online]. Recuperado de: https://www.dge.gob.pe/portal/docs/asis/Asis_mortalidad.pdf&nbsp;</li><li>La República. Entrevista, “Ahora la tecnología ayuda a controlar la diabetes”, recuperada de: https://larepublica.pe/la-contra/1257878-ahora-tecnologia-ayuda-controlar-diabetes/</li><li>-Ministerio de Salud. “Uno de cada tres diabéticos desarrolla ceguera a causa de retinopatía diabética”. Disponible en: https://www.gob.pe/institucion/minsa/noticias/22603-uno-de-cada-tres-diabeticos-desarrollara-ceguera-a-causa-de-la-retinopatia-diabetica</li><li>-Organización Mundial de la Salud. (2016). “Informe mundial sobre la diabetes”. Recuperado de https://apps.who.int/iris/bitstream/handle/10665/254649/9789243565255-spa.pdf;jsessionid=1D3CF5407F9F241CDC806D82AEF1FAD1?sequence=1</li><li>-Organización Mundial de la Salud. (2016). Perfiles de los países para la diabetes: Perú.  Disponible en: https://www.who.int/diabetes/country-profiles/per_es.pdf?ua=1</li><li>-Psicodiabetes 2007. JIMÉNEZ, María y DÁVILA, Mariel. Av. Psicol. Latinoam. [online]</li><li>-Redacción EC. (2018) “Diabetes causa 7 de cada 10 amputaciones de pies y piernas”. Recuperado de: https://elcomercio.pe/lima/diabetes-causa-7-10-amputaciones-pies-piernas-297052</li><li>-Seclén, S. (2015). Diabetes Mellitus en el Perú: hacia dónde vamos. Rev Med Hered, 26(1). Recuperado de: http://www.scielo.org.pe/scielo.php?script=sci_arttext&amp;pid=S1018-130X2015000100001</li><li>-Yagihashi, S. (2018). \"Clinical Application of Photoacoustic Imaging to the Evaluation of Diabetic Polyneuropathy\". Disponible en https://diabetes.diabetesjournals.org/content/67/Supplement_1/582-P</li><li>-Zhong, H., Duan, T., Lan, H., Zhou, M., &amp; Gao, F. (2018). Review of Low-Cost Photoacoustic Sensing and Imaging Based on Laser Diode and Light-Emitting Diode. Sensors (Basel, Switzerland), 18(7), 2264. doi:10.3390/s18072264</li>\n                </ul>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rFfPmSNJWM",
          "_anchor": "content12-1a",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "gpi5.html": {
      "settings": {
        "main": true,
        "title": "Procesos de Innovación en Bioingeniería - Grupo 5",
        "meta_descr": "",
        "header_custom": "",
        "footer_custom": "",
        "html_before": ""
      },
      "components": [
        {
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "-webkit-flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".navbar-expand": {
                "flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\" checked>\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\" checked>\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#c1c1c1\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\">\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#ffffff\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#333333\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"gpi5.html\">\n                         <img src=\"@PROJECT_PATH@/assets/images/icono-1-192x192.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\" title>\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"gpi5.html\" data-app-placeholder=\"Type Text\">Grupo 5</a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-4\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\"><li class=\"nav-item\">\n                    <a class=\"nav-link link text-white\" href=\"https://mobirise.com\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">\n                        </a>\n                </li>\n                <li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page5.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Problema</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page2.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">El Usuario</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page3.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Estado del Arte</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page4.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">La Propuesta</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page1.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Entregables</a></li><li class=\"nav-item\"><a class=\"nav-link link text-white\" href=\"page6.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\">Bibliografía</a></li></ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-buttons mbr-section-btn\"><a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a></div>\n        </div>\n    </nav>\n</section>",
          "_cid": "qTkzRZLJNu",
          "_anchor": "menu1-0",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "H1": {
              "color": "#232323"
            },
            ".mbr-text, .mbr-section-btn": {
              "color": "#232323"
            }
          },
          "_name": "header2",
          "_customHTML": "<section group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{\n         'mbr-fullscreen': fullScreen,\n         'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/20191023-110507-2000x1125.jpeg\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#073B4C\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#c4bc3b\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container align-center\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"mbr-white col-md-10\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">Grupo 5</h1>\n                <h3 class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                    Beautiful mobile websites\n                </h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">Somos un grupo de estudiantes del segundo ciclo de la carrera profesional de Ingeniería Biomédica que busca ofrecer una propuesta de solución innovadora ante la problemática de la diabetes.&nbsp;</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">EL PROBLEMA</a>\n                    <a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">EL USUARIO</a>  <a class=\"btn btn-md btn-black\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">ESTADO DEL ARTE</a> <a class=\"btn btn-md btn-success\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">LA PROPUESTA</a></div>\n            </div>\n        </div>\n    </div>\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "qTkA127IK8",
          "_anchor": "header2-1",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "color": "#767676"
            },
            ".media-container-row": {
              "-webkit-flex-wrap": "wrap",
              "-ms-flex-wrap": "wrap",
              "flex-wrap": "wrap"
            },
            ".mbr-text": {
              "color": "#232323"
            },
            ".mbr-author-desc": {
              "display": "block",
              "color": "#767676"
            },
            ".mbr-author-name": {
              "color": "#232323"
            },
            ".mbr-testimonial": {
              ".panel-item": {
                "background-color": "@cardsColor"
              },
              ".card-block": {
                "-webkit-flex-grow": "0",
                "flex-grow": "0",
                "padding": "2.4rem 2.4rem 0 2.4rem",
                ".testimonial-photo": {
                  "display": "inline-block",
                  "width": "120px",
                  "height": "120px",
                  "margin-bottom": "1.6rem",
                  "overflow": "hidden",
                  "border-radius": "50%",
                  "img": {
                    "width": "100%",
                    "min-width": "100%",
                    "min-height": "100%"
                  }
                }
              },
              ".card-footer": {
                "padding-bottom": "2.4rem",
                "border-top": "0",
                "padding-top": "1rem",
                "word-wrap": "break-word",
                "word-break": "break-word",
                "background": "none"
              }
            },
            "@media (max-width: 300px)": {
              ".testimonial-photo": {
                "width": "100% !important",
                "height": "auto !important"
              }
            }
          },
          "_name": "testimonials1",
          "_customHTML": "<section class=\"testimonials1\" group=\"Testimonials\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n     <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"3\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"5\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show Images\" name=\"showImages\" checked>\n        <input type=\"checkbox\" title=\"Show Name\" name=\"showName\" checked>\n        <input type=\"checkbox\" title=\"Show Biography\" name=\"showBio\" checked>\n\n        <input type=\"color\" title=\"Cards Color\" name=\"cardsColor\" value=\"#f7ed4a\">\n        <select title=\"Cards Count\" name=\"TestimonialsCount\">\n         <option value=\"1\">1</option>\n         <option value=\"2\">2</option>\n         <option value=\"3\">3</option>\n         <option value=\"4\">4</option>\n         <option value=\"5\" selected>5</option>\n         <option value=\"6\">6</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background2.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#efefef\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.8\" condition=\"overlay && bg.type !== 'color'\"> \n    <!-- End block parameters --> \n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"title col-12 align-center\">\n                <h2 class=\"pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\">\n                    NOSOTROS</h2>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\" data-app-selector=\".mbr-section-subtitle\">Somos los integrantes del grupo número 5 del curso Procesos de Innovación en Bioingeniería</h3>\n            </div>\n        </div>\n    </div>\n\n    <div class=\"container pt-3 mt-2\">\n        <div class=\"media-container-row\">\n            <div class=\"mbr-testimonial p-3 align-center col-12 col-md-6\" mbr-class=\"{'col-lg-4': TestimonialsCount > 2 }\">\n                <div class=\"panel-item p-3\">\n                    <div class=\"card-block\">\n                        <div class=\"testimonial-photo\" mbr-if=\"showImages\">\n                            <img src=\"@PROJECT_PATH@/assets/images/20191023-110417-240x272.jpeg\" alt title>\n                        </div>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\">Estudiante de segundo ciclo del curso Procesos de Innovación en Bioingeniería. Quiere especializarse en Señales e Imágenes médicas</p>\n                    </div>\n                    <div class=\"card-footer\">\n                        <div class=\"mbr-author-name mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showName\" data-app-selector=\".mbr-author-name\" mbr-text>Adrián Hernández Vega</div>\n                        <small class=\"mbr-author-desc mbr-italic mbr-light mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showBio\" data-app-selector=\".mbr-author-desc\" mbr-text>Integrante</small>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"mbr-testimonial p-3 align-center col-12 col-md-6\" mbr-class=\"{'col-lg-4': TestimonialsCount > 2 }\" mbr-if=\"TestimonialsCount>1\">\n                <div class=\"panel-item p-3\">\n                    <div class=\"card-block\">\n                        <div class=\"testimonial-photo\" mbr-if=\"showImages\">\n                            <img src=\"@PROJECT_PATH@/assets/images/20191023-110354-240x191.jpeg\" alt title>\n                        </div>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\">\n                           Estudiante de segundo ciclo del curso Procesos de Innovación en Bioingeniería. Quiere especializarse en Biomecánica y Rehabilitación</p>\n                    </div>\n                    <div class=\"card-footer\">\n                        <div class=\"mbr-author-name mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showName\" data-app-selector=\".mbr-author-name\" mbr-text>Jimena León Casamayor</div>\n                        <small class=\"mbr-author-desc mbr-italic mbr-light mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showBio\" data-app-selector=\".mbr-author-desc\" mbr-text>\n                               Integrante\n                        </small>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"mbr-testimonial p-3 align-center col-12 col-md-6\" mbr-class=\"{'col-lg-4': TestimonialsCount > 2 }\" mbr-if=\"TestimonialsCount>2\">\n                <div class=\"panel-item p-3\">\n                    <div class=\"card-block\">\n                        <div class=\"testimonial-photo\" mbr-if=\"showImages\">\n                            <img src=\"@PROJECT_PATH@/assets/images/20191023-110321-240x186.jpeg\" alt title>\n                        </div>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\">\n                           Estudiante de segundo ciclo del curso Procesos de Innovación en Bioingeniería. Quiere especializarse en Señales e Imágenes médicas\n                        </p>\n                    </div>\n                    <div class=\"card-footer\">\n                        <div class=\"mbr-author-name mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showName\" data-app-selector=\".mbr-author-name\" mbr-text>\n                             Fiorella Ojeda Quispe</div>\n                        <small class=\"mbr-author-desc mbr-italic mbr-light mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showBio\" data-app-selector=\".mbr-author-desc\" mbr-text>Integrante</small>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"mbr-testimonial p-3 align-center col-12 col-md-6\" mbr-class=\"{'col-lg-4': TestimonialsCount > 2 }\" mbr-if=\"TestimonialsCount>3\">\n                <div class=\"panel-item p-3\">\n                    <div class=\"card-block\">\n                        <div class=\"testimonial-photo\" mbr-if=\"showImages\">\n                            <img src=\"@PROJECT_PATH@/assets/images/20191023-110332-240x200.jpeg\" alt title>\n                        </div>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\">\n                           Estudiante de segundo ciclo del curso Procesos de Innovación en Bioingeniería. Quiere especializarse en Ingeniería Clínica</p>\n                    </div>\n                    <div class=\"card-footer\">\n                        <div class=\"mbr-author-name mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showName\" data-app-selector=\".mbr-author-name\" mbr-text>Alejandro Jave Chang</div>\n                        <small class=\"mbr-author-desc mbr-italic mbr-light mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showBio\" data-app-selector=\".mbr-author-desc\" mbr-text>Integrante</small>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"mbr-testimonial p-3 align-center col-12 col-md-6\" mbr-class=\"{'col-lg-4': TestimonialsCount > 2 }\" mbr-if=\"TestimonialsCount>4\">\n                <div class=\"panel-item p-3\">\n                    <div class=\"card-block\">\n                        <div class=\"testimonial-photo\" mbr-if=\"showImages\">\n                            <img src=\"@PROJECT_PATH@/assets/images/20191023-110221-240x195.jpeg\" alt title>\n                        </div>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\">\n                           Estudiante de segundo ciclo del curso Procesos de Innovación en Bioingeniería. Quiere especializarse en Ingeniería de Tejidos y Biomateriales</p>\n                    </div>\n                    <div class=\"card-footer\">\n                        <div class=\"mbr-author-name mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showName\" data-app-selector=\".mbr-author-name\" mbr-text>Ricardo Muñoz Quiroz</div>\n                        <small class=\"mbr-author-desc mbr-italic mbr-light mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showBio\" data-app-selector=\".mbr-author-desc\" mbr-text>\n                               Integrante\n                        </small>\n                    </div>\n                </div>\n            </div>\n\n            <div class=\"mbr-testimonial p-3 align-center col-12 col-md-6\" mbr-class=\"{'col-lg-4': TestimonialsCount > 2 }\" mbr-if=\"TestimonialsCount>5\">\n                <div class=\"panel-item p-3\">\n                    <div class=\"card-block\">\n                        <div class=\"testimonial-photo\" mbr-if=\"showImages\">\n                            <img src=\"../_images/face2.jpg\">\n                        </div>\n                        <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".mbr-text\">\n                           Lorem ipsum dolor sit amet, consectetur adipisicing elit. Excepturi, aspernatur, voluptatibus, atque, tempore molestiae.\n                    </p></div>\n                    <div class=\"card-footer\">\n                        <div class=\"mbr-author-name mbr-bold mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showName\" data-app-selector=\".mbr-author-name\" mbr-text>\n                             John Smith\n                        </div>\n                        <small class=\"mbr-author-desc mbr-italic mbr-light mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showBio\" data-app-selector=\".mbr-author-desc\" mbr-text>\n                               Developer\n                        </small>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>   \n</section>",
          "_cid": "rFaEKEpJpt",
          "_anchor": "testimonials1-9",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "h4": {
              "font-weight": "500",
              "color": "#ffffff"
            },
            "p": {
              "color": "#ffffff"
            },
            ".card": {
              "margin-bottom": "2rem"
            },
            ".card-img": {
              "border-radius": "0",
              "padding": "2rem 2rem 0 2rem",
              "& when (@cardBg)": {
                "background-color": "@cardColor"
              },
              "span": {
                "font-size": "100px",
                "color": "#ffffff"
              }
            },
            ".card-box": {
              "padding-bottom": "2rem",
              ".card-title": {
                "margin": "0",
                "padding": "2rem 2rem 0 2rem"
              },
              ".mbr-text": {
                "margin-bottom": "0",
                "padding": "2rem 2rem 0 2rem"
              },
              ".mbr-section-btn": {
                "padding-top": "1rem",
                "a": {
                  "margin-top": "1rem",
                  "margin-bottom": "0"
                }
              },
              "& when (@cardBg)": {
                "background-color": "@cardColor",
                "& when (@translucency)": {
                  "background": "linear-gradient(@cardColor, transparent)"
                }
              }
            }
          },
          "_name": "features8",
          "_customHTML": "<section class=\"features8\" group=\"Features\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n        <input type=\"checkbox\" title=\"Card Background\" name=\"cardBg\" checked>\n        <input type=\"color\" title=\"Card Color\" name=\"cardColor\" value=\"#c4bc3b\" condition=\"cardBg\">\n        <input type=\"checkbox\" title=\"Translucency\" name=\"translucency\" condition=\"cardBg\" checked>\n        <select title=\"Cards\" name=\"cardsAmount\">\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\" selected>3</option>\n            <option value=\"4\">4</option>\n        </select>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/web1-1613x1073.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#4f4943\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" checked condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n\n            <div class=\"card  col-12 col-md-6\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-img\">\n                    <span mbr-icon class=\"mbr-iconfont mbri-laptop\"></span>\n                </div>\n                <div class=\"card-box align-center\">\n                    <h4 class=\"card-title mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title, .card-img\">Entregable 1</h4>\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                       El porblema, usuario y estado del arte</p>\n                    <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn text-center\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a href=\"https://mobirise.co\" class=\"btn btn-success\" data-app-placeholder=\"Type Text\">Más<br>\n                        </a></div>\n                </div>\n            </div>\n\n            <div class=\"card  col-12 col-md-6\" mbr-if=\"cardsAmount > 1\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-img\">\n                    <span mbr-icon class=\"mbri-touch mbr-iconfont\"></span>\n                </div>\n                <div class=\"card-box align-center\">\n                    <h4 class=\"card-title mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title, .card-img\">Entregable 2</h4>\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">&nbsp;&nbsp;</p>\n                    <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn text-center\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a href=\"https://mobirise.co\" class=\"btn btn-success\" data-app-placeholder=\"Type Text\">\n                            Más</a></div>\n                </div>\n            </div>\n\n            <div class=\"card  col-12 col-md-6\" mbr-if=\"cardsAmount > 2\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-img\">\n                    <span mbr-icon class=\"mbri-responsive mbr-iconfont\"></span>\n                </div>\n                <div class=\"card-box align-center\">\n                    <h4 class=\"card-title mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title, .card-img\">Entregable 3</h4>\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">&nbsp; &nbsp;&nbsp;</p>\n                    <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn text-center\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a href=\"https://mobirise.co\" class=\"btn btn-success\" data-app-placeholder=\"Type Text\">\n                            Más</a></div>\n                </div>\n            </div>\n\n            <div class=\"card  col-12 col-md-6\" mbr-if=\"cardsAmount > 3\" mbr-class=\"{'col-lg-3': cardsAmount == '4',\n                             'col-lg-4': cardsAmount == '3'}\">\n                <div class=\"card-img\">\n                    <span mbr-icon class=\"mbri-bootstrap mbr-iconfont\"></span>\n                </div>\n                <div class=\"card-box align-center\">\n                    <h4 class=\"card-title mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showTitle\" data-app-selector=\".card-title, .card-img\">\n                        No Coding\n                    </h4>\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\">\n                       Mobirise is an easy website builder - just drop site elements to your page, add content and style it to look the way you like.\n                    </p>\n                    <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn text-center\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\">\n                        <a href=\"https://mobirise.co\" class=\"btn btn-secondary\">\n                            More\n                        </a>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "rDW1Da7GVc",
          "_anchor": "features8-5",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            ".content": {
              "@media (max-width: 767px)": {
                "text-align": "center",
                "> div:not(:last-child)": {
                  "margin-bottom": "2rem"
                }
              }
            },
            ".media-wrap": {
              "@media (max-width: 767px)": {
                "margin-bottom": "1rem"
              },
              ".mbr-iconfont-logo": {
                "font-size": "7.5rem",
                "color": "#f36"
              },
              "img": {
                "height": "6rem"
              }
            },
            ".footer-lower": {
              ".copyright": {
                "@media (max-width: 767px)": {
                  "margin-bottom": "1rem",
                  "text-align": "center"
                }
              },
              "hr": {
                "margin": "1rem 0",
                "border-color": "#fff",
                "opacity": ".05"
              },
              ".social-list": {
                "padding-left": "0",
                "margin-bottom": "0",
                "list-style": "none",
                "display": "flex",
                "flex-wrap": "wrap",
                "justify-content": "flex-end",
                "-webkit-justify-content": "flex-end",
                ".mbr-iconfont-social": {
                  "font-size": "1.3rem",
                  "color": "#fff"
                },
                ".soc-item": {
                  "margin": "0 .5rem"
                },
                "a": {
                  "margin": "0",
                  "opacity": ".5",
                  "-webkit-transition": ".2s linear",
                  "transition": ".2s linear",
                  "&:hover": {
                    "opacity": "1"
                  }
                },
                "@media (max-width: 767px)": {
                  "justify-content": "center",
                  "-webkit-justify-content": "center"
                }
              }
            }
          },
          "_name": "footer1",
          "_customHTML": "<section group=\"Footers\" mbr-class=\"{'mbr-reveal': reveal, 'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->  \n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"4\">\n        <input type=\"checkbox\" title=\"Show Copyright\" name=\"showCopyright\" checked>\n        <select title=\"Icons\" name=\"iconsCount\">\n            <option value=\"0\" selected>0</option>\n            <option value=\"1\">1</option>\n            <option value=\"2\">2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\">6</option>\n        </select>\n        <input type=\"checkbox\" title=\"Reveal effect\" name=\"reveal\">\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#2e2e2e\" selected>\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#3C3C3C\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.5\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row content text-white\">\n            <div class=\"col-12 col-md-3\">\n                <div class=\"media-wrap\">\n                    <a href=\"https://mobirise.com/\">\n                        <img src=\"@PROJECT_PATH@/assets/images/icono-192x192.png\" alt=\"Mobirise\" title>\n                    </a>\n                </div>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">&nbsp; &nbsp;</h5>\n                <p class=\"mbr-text\">&nbsp; &nbsp;</p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\">\n                    Contáctanos</h5>\n                <p class=\"mbr-text\">\n                    Email: pibgrupo5@gmail.com&nbsp;<br><br><br></p>\n            </div>\n            <div class=\"col-12 col-md-3 mbr-fonts-style\" mbr-theme-style=\"display-7\">\n                <h5 class=\"pb-3\"><p>&nbsp;<br></p></h5>\n                <p class=\"mbr-text\">&nbsp;&nbsp;</p>\n            </div>\n        </div>\n        <div class=\"footer-lower\" mbr-if=\"showCopyright\">\n            <div class=\"media-container-row\">\n                <div class=\"col-sm-12\">\n                    <hr>\n                </div>\n            </div>\n            <div class=\"media-container-row mbr-white\">\n                <div class=\"col-sm-6 copyright\">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".copyright > p\">\n                        © Copyright 2017 Mobirise - All Rights Reserved\n                    </p>\n                </div>\n                <div class=\"col-md-6\">\n                    <div class=\"social-list align-right\" mbr-if=\"iconsCount > 0\">\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>0\">\n                            <a href=\"https://twitter.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"mbr-iconfont mbr-iconfont-social socicon-googleplus socicon\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>1\">\n                            <a href=\"https://www.facebook.com/pages/Mobirise/1616226671953247\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-facebook socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>2\">\n                            <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-youtube socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>3\">\n                            <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-instagram socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>4\">\n                            <a href=\"https://plus.google.com/u/0/+Mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-googleplus socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>5\">\n                            <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-behance socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "qTkAaeaxX5",
          "_anchor": "footer1-2",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    }
  }
}
