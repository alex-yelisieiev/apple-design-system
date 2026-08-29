/* Menus */

box-sizing: border-box;

position: relative;
width: 340px;
height: 1420px;

background: #F5F5F5;
border: 1px solid rgba(0, 0, 0, 0.4);
border-radius: 2px;


/* Separator */

position: relative;
width: 194px;
height: 11px;
left: 50px;
top: 1120px;



/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Header */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 0px 4px 18px;
gap: 10px;

position: relative;
width: 194px;
height: 21px;
left: 50px;
top: 1161px;



/* Header */

width: 37px;
height: 12px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 12px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;

color: #727272;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* _Menu Item */

box-sizing: border-box;

position: relative;
width: 200px;
height: 510px;
left: 50px;
top: 420px;

border: 1px dashed #9747FF;
border-radius: 5px;


/* Type=Submenu, Menu has Selection=True, State=Disabled */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 0px 0px 12px;
gap: 8px;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 470px;



/* Frame */

width: 4px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;



/* Label */

width: 96px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;


/* Type=Submenu, Menu has Selection=True, State=Hover + Key */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 0px 0px 12px;
gap: 8px;
isolation: isolate;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 410px;

border-radius: 8px;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, #0088FF, #0088FF), linear-gradient(0deg, rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), rgba(0, 0, 0, 0.05);
background-blend-mode: plus-darker, color-dodge, normal;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Frame */

width: 4px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* Symbol */

width: 12px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;



/* Label */

width: 96px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 1;
z-index: 3;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 4;
align-self: stretch;
flex-grow: 0;
z-index: 4;


/* Type=Submenu, Menu has Selection=True, State=Hover */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 0px 0px 12px;
gap: 8px;
isolation: isolate;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 440px;

border-radius: 8px;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: #E6E6E6;
mix-blend-mode: plus-darker;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Frame */

width: 4px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 96px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 1;
z-index: 3;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 4;
align-self: stretch;
flex-grow: 0;
z-index: 4;


/* Type=Submenu, Menu has Selection=True, State=Idle */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 0px 0px 12px;
gap: 8px;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 380px;



/* Frame */

width: 4px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 96px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;


/* Type=Submenu, Menu has Selection=False, State=Disabled */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 330px;



/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;



/* Label */

width: 120px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Type=Submenu, Menu has Selection=False, State=Hover + Key */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;
isolation: isolate;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 270px;

border-radius: 8px;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, #0088FF, #0088FF), linear-gradient(0deg, rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), rgba(0, 0, 0, 0.05);
background-blend-mode: plus-darker, color-dodge, normal;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Symbol */

width: 12px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;



/* Label */

width: 120px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;
z-index: 2;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* Type=Submenu, Menu has Selection=False, State=Hover */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;
isolation: isolate;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 300px;

border-radius: 8px;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: #E6E6E6;
mix-blend-mode: plus-darker;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 120px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;
z-index: 2;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* Type=Submenu, Menu has Selection=False, State=Idle */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 240px;



/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 120px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Type=Action, Menu has Selection=True, State=Disabled */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 0px 0px 12px;
gap: 8px;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 190px;



/* Frame */

width: 4px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀆅 */

position: absolute;
width: 12px;
left: -6px;
top: 0px;
bottom: 0px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 16px;
/* or 160% */
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;



/* Label */

width: 83px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Type=Action, Menu has Selection=True, State=Hover */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 0px 0px 12px;
gap: 8px;
isolation: isolate;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 160px;

border-radius: 8px;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, #0088FF, #0088FF), linear-gradient(0deg, rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), rgba(0, 0, 0, 0.05);
background-blend-mode: plus-darker, color-dodge, normal;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Frame */

width: 4px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* 􀆅 */

position: absolute;
width: 12px;
left: -6px;
top: 0px;
bottom: 0px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 16px;
/* or 160% */
display: flex;
align-items: center;

color: #FFFFFF;



/* Symbol */

width: 12px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;



/* Label */

width: 83px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

/* White */
color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 1;
z-index: 3;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 4;
align-self: stretch;
flex-grow: 0;
z-index: 4;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Type=Action, Menu has Selection=True, State=Idle */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px 0px 0px 12px;
gap: 8px;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 130px;



/* Frame */

width: 4px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀆅 */

position: absolute;
width: 12px;
left: -6px;
top: 0px;
bottom: 0px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 16px;
/* or 160% */
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 83px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Type=Action, Menu has Selection=False, State=Disabled */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 80px;



/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;



/* Label */

width: 107px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Type=Action, Menu has Selection=False, State=Hover */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;
isolation: isolate;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 50px;

border-radius: 8px;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, #0088FF, #0088FF), linear-gradient(0deg, rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), rgba(0, 0, 0, 0.05);
background-blend-mode: plus-darker, color-dodge, normal;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Symbol */

width: 12px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;



/* Label */

width: 107px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

/* White */
color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;
z-index: 2;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Type=Action, Menu has Selection=False, State=Idle */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

position: absolute;
width: 160px;
height: 24px;
left: 20px;
top: 20px;



/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 107px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* _Shortcuts */

box-sizing: border-box;

position: relative;
width: 100px;
height: 90px;
left: 50px;
top: 970px;

border: 1px dashed #9747FF;
border-radius: 5px;


/* State=Disabled */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

position: absolute;
width: 64px;
height: 16px;
left: 20px;
top: 60px;

mix-blend-mode: plus-darker;


/* 􀆍 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* State=Hover */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

position: absolute;
width: 64px;
height: 16px;
left: 20px;
top: 40px;



/* 􀆍 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* State=Idle */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

position: absolute;
width: 64px;
height: 16px;
left: 20px;
top: 20px;



/* 􀆍 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Menu */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 12px;
isolation: isolate;

position: relative;
width: 250px;
height: 328px;
left: 50px;
top: 50px;



/* _Menu BG */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Fill */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, rgba(245, 245, 245, 0.67), rgba(245, 245, 245, 0.67)), #262626;
background-blend-mode: normal, color-dodge;
box-shadow: 0px 0px 2px rgba(0, 0, 0, 0.1), 0px 0px 25px rgba(0, 0, 0, 0.16);
border-radius: 13px;


/* Glass Effect */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: rgba(0, 0, 0, 0.004);
border-radius: 13px;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 160px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 4;
align-self: stretch;
flex-grow: 0;
z-index: 4;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;
isolation: isolate;

width: 226px;
height: 24px;

border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 5;
align-self: stretch;
flex-grow: 0;
z-index: 5;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, #0088FF, #0088FF), linear-gradient(0deg, rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), rgba(0, 0, 0, 0.05);
background-blend-mode: plus-darker, color-dodge, normal;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Symbol */

width: 12px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;



/* Label */

width: 147px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

/* White */
color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;
z-index: 2;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 51px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 6;
align-self: stretch;
flex-grow: 0;
z-index: 6;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 7;
align-self: stretch;
flex-grow: 0;
z-index: 7;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 8;
align-self: stretch;
flex-grow: 0;
z-index: 8;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 160px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 9;
align-self: stretch;
flex-grow: 0;
z-index: 9;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 10;
align-self: stretch;
flex-grow: 0;
z-index: 10;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 11;
align-self: stretch;
flex-grow: 0;
z-index: 11;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 12;
align-self: stretch;
flex-grow: 0;
z-index: 12;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Header */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 0px 4px 18px;
gap: 10px;

width: 226px;
height: 21px;


/* Inside auto layout */
flex: none;
order: 13;
align-self: stretch;
flex-grow: 0;
z-index: 13;


/* Header */

width: 37px;
height: 12px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 12px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;

color: #727272;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 14;
align-self: stretch;
flex-grow: 0;
z-index: 14;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 15;
align-self: stretch;
flex-grow: 0;
z-index: 15;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* _Menu BG */

position: relative;
width: 160px;
height: 160px;
left: 50px;
top: 1220px;



/* Fill */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, rgba(245, 245, 245, 0.67), rgba(245, 245, 245, 0.67)), #262626;
background-blend-mode: normal, color-dodge;
box-shadow: 0px 0px 2px rgba(0, 0, 0, 0.1), 0px 0px 25px rgba(0, 0, 0, 0.16);
border-radius: 13px;


/* Glass Effect */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: rgba(0, 0, 0, 0.004);
border-radius: 13px;


/* Header */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 0px;
gap: 32px;

position: relative;
width: 1400px;
height: 242px;



/* Component */

width: 1400px;
height: 60px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 56px;
line-height: 60px;
/* identical to box height, or 107% */
display: flex;
align-items: center;
letter-spacing: -0.28px;

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* Description */

width: 1400px;
height: 68px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 400;
font-size: 28px;
line-height: 34px;
/* or 121% */

color: rgba(0, 0, 0, 0.85);


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;


/* Frame */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 8px 0px;
gap: 16px;

width: 1400px;
height: 50px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Link */

width: 1400px;
height: 34px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 400;
font-size: 28px;
line-height: 34px;
/* identical to box height, or 121% */
display: flex;
align-items: center;
text-decoration-line: underline;

color: #0088FF;


/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* Link */

display: none;
width: 1400px;
height: 34px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 400;
font-size: 28px;
line-height: 34px;
/* identical to box height, or 121% */
display: flex;
align-items: center;

color: #0088FF;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;


/* Examples */

box-sizing: border-box;

position: relative;
width: 1330px;
height: 430px;

background: #ECEBEB;
border: 1px solid rgba(0, 0, 0, 0.1);
border-radius: 2px;


/* Menu */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 12px;
isolation: isolate;

position: relative;
width: 250px;
height: 328px;
left: 764px;
top: 50px;



/* _Menu BG */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Fill */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, rgba(245, 245, 245, 0.67), rgba(245, 245, 245, 0.67)), #262626;
background-blend-mode: normal, color-dodge;
box-shadow: 0px 0px 2px rgba(0, 0, 0, 0.1), 0px 0px 25px rgba(0, 0, 0, 0.16);
border-radius: 13px;


/* Glass Effect */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: rgba(0, 0, 0, 0.004);
border-radius: 13px;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 160px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 4;
align-self: stretch;
flex-grow: 0;
z-index: 4;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;
isolation: isolate;

width: 226px;
height: 24px;

border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 5;
align-self: stretch;
flex-grow: 0;
z-index: 5;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, #0088FF, #0088FF), linear-gradient(0deg, rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), rgba(0, 0, 0, 0.05);
background-blend-mode: plus-darker, color-dodge, normal;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Symbol */

width: 12px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;



/* Label */

width: 147px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

/* White */
color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;
z-index: 2;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 51px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 6;
align-self: stretch;
flex-grow: 0;
z-index: 6;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 7;
align-self: stretch;
flex-grow: 0;
z-index: 7;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 8;
align-self: stretch;
flex-grow: 0;
z-index: 8;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 160px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 9;
align-self: stretch;
flex-grow: 0;
z-index: 9;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 10;
align-self: stretch;
flex-grow: 0;
z-index: 10;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 11;
align-self: stretch;
flex-grow: 0;
z-index: 11;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 12;
align-self: stretch;
flex-grow: 0;
z-index: 12;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Header */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 0px 4px 18px;
gap: 10px;

width: 226px;
height: 21px;


/* Inside auto layout */
flex: none;
order: 13;
align-self: stretch;
flex-grow: 0;
z-index: 13;


/* Header */

width: 37px;
height: 12px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 12px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;

color: #727272;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 14;
align-self: stretch;
flex-grow: 0;
z-index: 14;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 15;
align-self: stretch;
flex-grow: 0;
z-index: 15;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Menu */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 12px;
isolation: isolate;

position: relative;
width: 250px;
height: 328px;
left: 1034px;
top: 50px;



/* _Menu BG */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Fill */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, rgba(245, 245, 245, 0.67), rgba(245, 245, 245, 0.67)), #262626;
background-blend-mode: normal, color-dodge;
box-shadow: 0px 0px 2px rgba(0, 0, 0, 0.1), 0px 0px 25px rgba(0, 0, 0, 0.16);
border-radius: 13px;


/* Glass Effect */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: rgba(0, 0, 0, 0.004);
border-radius: 13px;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 160px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 4;
align-self: stretch;
flex-grow: 0;
z-index: 4;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;
isolation: isolate;

width: 226px;
height: 24px;

border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 5;
align-self: stretch;
flex-grow: 0;
z-index: 5;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, #0088FF, #0088FF), linear-gradient(0deg, rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), rgba(0, 0, 0, 0.05);
background-blend-mode: plus-darker, color-dodge, normal;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Symbol */

width: 12px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;



/* Label */

width: 147px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

/* White */
color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;
z-index: 2;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 51px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 6;
align-self: stretch;
flex-grow: 0;
z-index: 6;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 7;
align-self: stretch;
flex-grow: 0;
z-index: 7;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 8;
align-self: stretch;
flex-grow: 0;
z-index: 8;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 160px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 9;
align-self: stretch;
flex-grow: 0;
z-index: 9;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 10;
align-self: stretch;
flex-grow: 0;
z-index: 10;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 11;
align-self: stretch;
flex-grow: 0;
z-index: 11;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 12;
align-self: stretch;
flex-grow: 0;
z-index: 12;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Header */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 0px 4px 18px;
gap: 10px;

width: 226px;
height: 21px;


/* Inside auto layout */
flex: none;
order: 13;
align-self: stretch;
flex-grow: 0;
z-index: 13;


/* Header */

width: 37px;
height: 12px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 12px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;

color: #727272;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 14;
align-self: stretch;
flex-grow: 0;
z-index: 14;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 15;
align-self: stretch;
flex-grow: 0;
z-index: 15;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Menu */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 12px;
isolation: isolate;

position: relative;
width: 250px;
height: 328px;
left: 494px;
top: 50px;



/* _Menu BG */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Fill */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, rgba(245, 245, 245, 0.67), rgba(245, 245, 245, 0.67)), #262626;
background-blend-mode: normal, color-dodge;
box-shadow: 0px 0px 2px rgba(0, 0, 0, 0.1), 0px 0px 25px rgba(0, 0, 0, 0.16);
border-radius: 13px;


/* Glass Effect */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: rgba(0, 0, 0, 0.004);
border-radius: 13px;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 160px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 4;
align-self: stretch;
flex-grow: 0;
z-index: 4;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;
isolation: isolate;

width: 226px;
height: 24px;

border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 5;
align-self: stretch;
flex-grow: 0;
z-index: 5;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, #0088FF, #0088FF), linear-gradient(0deg, rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), rgba(0, 0, 0, 0.05);
background-blend-mode: plus-darker, color-dodge, normal;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Symbol */

width: 12px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;



/* Label */

width: 147px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

/* White */
color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;
z-index: 2;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 51px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 6;
align-self: stretch;
flex-grow: 0;
z-index: 6;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 7;
align-self: stretch;
flex-grow: 0;
z-index: 7;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 8;
align-self: stretch;
flex-grow: 0;
z-index: 8;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 160px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 9;
align-self: stretch;
flex-grow: 0;
z-index: 9;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;



/* Label */

width: 173px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 10;
align-self: stretch;
flex-grow: 0;
z-index: 10;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 11;
align-self: stretch;
flex-grow: 0;
z-index: 11;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Chevron */

width: 12px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Separator */

width: 226px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 12;
align-self: stretch;
flex-grow: 0;
z-index: 12;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Header */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 0px 4px 18px;
gap: 10px;

width: 226px;
height: 21px;


/* Inside auto layout */
flex: none;
order: 13;
align-self: stretch;
flex-grow: 0;
z-index: 13;


/* Header */

width: 37px;
height: 12px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 12px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;

color: #727272;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 14;
align-self: stretch;
flex-grow: 0;
z-index: 14;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 226px;
height: 24px;


/* Inside auto layout */
flex: none;
order: 15;
align-self: stretch;
flex-grow: 0;
z-index: 15;


/* Symbol */

width: 12px;
height: 24px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 186px;
height: 24px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 13px;
line-height: 16px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Menu */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 12px;
isolation: isolate;

position: relative;
width: 210px;
height: 304px;
left: 264px;
top: 50px;



/* _Menu BG */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Fill */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, rgba(245, 245, 245, 0.67), rgba(245, 245, 245, 0.67)), #262626;
background-blend-mode: normal, color-dodge;
box-shadow: 0px 0px 2px rgba(0, 0, 0, 0.1), 0px 0px 25px rgba(0, 0, 0, 0.16);
border-radius: 13px;


/* Glass Effect */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: rgba(0, 0, 0, 0.004);
border-radius: 13px;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 186px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* Symbol */

width: 10px;
height: 22px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 135px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 186px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* Symbol */

width: 10px;
height: 22px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 122px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 186px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 186px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 4;
align-self: stretch;
flex-grow: 0;
z-index: 4;


/* Symbol */

width: 10px;
height: 22px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 135px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;
isolation: isolate;

width: 186px;
height: 22px;

border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 5;
align-self: stretch;
flex-grow: 0;
z-index: 5;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, #0088FF, #0088FF), linear-gradient(0deg, rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), rgba(0, 0, 0, 0.05);
background-blend-mode: plus-darker, color-dodge, normal;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Symbol */

width: 10px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;



/* Label */

width: 109px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

/* White */
color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;
z-index: 2;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 51px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 186px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 6;
align-self: stretch;
flex-grow: 0;
z-index: 6;


/* Symbol */

width: 10px;
height: 22px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 148px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 186px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 7;
align-self: stretch;
flex-grow: 0;
z-index: 7;


/* Symbol */

width: 10px;
height: 22px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 135px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 186px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 8;
align-self: stretch;
flex-grow: 0;
z-index: 8;


/* Symbol */

width: 10px;
height: 22px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 122px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 186px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 9;
align-self: stretch;
flex-grow: 0;
z-index: 9;


/* Symbol */

width: 10px;
height: 22px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;



/* Label */

width: 135px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 186px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 10;
align-self: stretch;
flex-grow: 0;
z-index: 10;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 186px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 11;
align-self: stretch;
flex-grow: 0;
z-index: 11;


/* Symbol */

width: 10px;
height: 22px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 148px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Chevron */

width: 12px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Separator */

width: 186px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 12;
align-self: stretch;
flex-grow: 0;
z-index: 12;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Header */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 4px 0px 3px 16px;
gap: 10px;

width: 186px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 13;
align-self: stretch;
flex-grow: 0;
z-index: 13;


/* Header */

width: 37px;
height: 12px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 12px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;

color: #727272;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 186px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 14;
align-self: stretch;
flex-grow: 0;
z-index: 14;


/* Symbol */

width: 10px;
height: 22px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 148px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 186px;
height: 22px;


/* Inside auto layout */
flex: none;
order: 15;
align-self: stretch;
flex-grow: 0;
z-index: 15;


/* Symbol */

width: 10px;
height: 22px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 148px;
height: 22px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Menu */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 5px 12px;
isolation: isolate;

position: relative;
width: 190px;
height: 269px;
left: 54px;
top: 50px;



/* _Menu BG */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Fill */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, rgba(245, 245, 245, 0.67), rgba(245, 245, 245, 0.67)), #262626;
background-blend-mode: normal, color-dodge;
box-shadow: 0px 0px 2px rgba(0, 0, 0, 0.1), 0px 0px 25px rgba(0, 0, 0, 0.16);
border-radius: 13px;


/* Glass Effect */

position: absolute;
left: 0px;
right: 0px;
top: 0px;
bottom: 0px;

background: rgba(0, 0, 0, 0.004);
border-radius: 13px;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 166px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* Symbol */

width: 6px;
height: 19px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 119px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 166px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
z-index: 2;


/* Symbol */

width: 6px;
height: 19px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 106px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 166px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 166px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 4;
align-self: stretch;
flex-grow: 0;
z-index: 4;


/* Symbol */

width: 6px;
height: 19px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 119px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;
isolation: isolate;

width: 166px;
height: 19px;

border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 5;
align-self: stretch;
flex-grow: 0;
z-index: 5;


/* BG */

position: absolute;
left: -7px;
right: -7px;
top: 0px;
bottom: 0px;

background: linear-gradient(0deg, #0088FF, #0088FF), linear-gradient(0deg, rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65)), rgba(0, 0, 0, 0.05);
background-blend-mode: plus-darker, color-dodge, normal;
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
z-index: 0;


/* Symbol */

width: 6px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
z-index: 1;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;



/* Label */

width: 93px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

/* White */
color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 1;
z-index: 2;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 51px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 3;
align-self: stretch;
flex-grow: 0;
z-index: 3;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #FFFFFF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 166px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 6;
align-self: stretch;
flex-grow: 0;
z-index: 6;


/* Symbol */

width: 6px;
height: 19px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 132px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 166px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 7;
align-self: stretch;
flex-grow: 0;
z-index: 7;


/* Symbol */

width: 6px;
height: 19px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 119px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 166px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 8;
align-self: stretch;
flex-grow: 0;
z-index: 8;


/* Symbol */

width: 6px;
height: 19px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 106px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 38px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 166px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 9;
align-self: stretch;
flex-grow: 0;
z-index: 9;


/* Symbol */

width: 6px;
height: 19px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;



/* Label */

width: 119px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

color: #BFBFBF;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 25px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Separator */

width: 166px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 10;
align-self: stretch;
flex-grow: 0;
z-index: 10;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Submenu */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 166px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 11;
align-self: stretch;
flex-grow: 0;
z-index: 11;


/* Symbol */

width: 6px;
height: 19px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 132px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Chevron */

width: 12px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;


/* Separator */

width: 166px;
height: 11px;


/* Inside auto layout */
flex: none;
order: 12;
align-self: stretch;
flex-grow: 0;
z-index: 12;


/* Separator */

position: absolute;
height: 1px;
left: -1.33px;
right: -1.33px;
top: calc(50% - 1px/2);

background: #E6E6E6;
mix-blend-mode: plus-darker;


/* Header */

/* Auto layout */
display: flex;
flex-direction: column;
align-items: flex-start;
padding: 3px 0px 2px 12px;
gap: 10px;

width: 166px;
height: 17px;


/* Inside auto layout */
flex: none;
order: 13;
align-self: stretch;
flex-grow: 0;
z-index: 13;


/* Header */

width: 37px;
height: 12px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 700;
font-size: 10px;
line-height: 12px;
/* identical to box height */
display: flex;
align-items: center;
text-align: center;

color: #727272;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 166px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 14;
align-self: stretch;
flex-grow: 0;
z-index: 14;


/* Symbol */

width: 6px;
height: 19px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
visibility: hidden;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 132px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;


/* Item */

/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;
gap: 8px;

width: 166px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 15;
align-self: stretch;
flex-grow: 0;
z-index: 15;


/* Symbol */

width: 6px;
height: 19px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 0;
align-self: stretch;
flex-grow: 0;


/* 􀉁 */

position: absolute;
width: 18px;
height: 16px;
left: calc(50% - 18px/2);
top: calc(50% - 16px/2 + 0.5px);

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 11px;
line-height: 13px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #1A1A1A;



/* Label */

width: 132px;
height: 19px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;

color: #1A1A1A;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 1;


/* Shortcuts */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 1px;

width: 12px;
height: 16px;

mix-blend-mode: plus-darker;

/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆍 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;


/* 􀆕 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;


/* 􀆝 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;


/* 􀆔 */

display: none;
width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 3;
flex-grow: 0;


/* A */

width: 12px;
height: 16px;

font-family: 'SF Pro';
font-style: normal;
font-weight: 510;
font-size: 10px;
line-height: 12px;
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'ss15' on;

color: #BFBFBF;


/* Inside auto layout */
flex: none;
order: 4;
flex-grow: 0;
