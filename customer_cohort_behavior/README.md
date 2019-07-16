{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 ArialMT;\f1\froman\fcharset0 TimesNewRomanPSMT;\f2\fswiss\fcharset0 Helvetica;
}
{\colortbl;\red255\green255\blue255;\red26\green26\blue26;\red255\green255\blue255;\red0\green0\blue0;
}
{\*\expandedcolortbl;;\cssrgb\c13333\c13333\c13333;\cssrgb\c100000\c100000\c100000;\cssrgb\c0\c0\c0;
}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\b\fs26 \cf2 \cb3 \expnd0\expndtw0\kerning0
Problem statement:
\b0 \cb1 \
\pard\pardeftab720\partightenfactor0
\cf2 \cb3 Assume that the business started in May 2017 and they sell products through 3 mediums:\cb1 \
\cb3 -
\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0 
\fs26 Store\cb1 \
\cb3 -
\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0 
\fs26 Dotcom\cb1 \
\cb3 -
\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0 
\fs26 Online grocery (OG)\cb1 \
\pard\pardeftab720\partightenfactor0

\f1\fs29\fsmilli14667 \cf2 \cb3 \'a0
\fs32 \cb1 \
\pard\pardeftab720\partightenfactor0

\f0\fs26 \cf2 \cb3 Customer science business partners would like to understand a couple of things:\cb1 \
\cb3 -
\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0 
\fs26 Who are our best customers ?\cb1 \
\cb3 -
\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0 
\fs26 What is the replenishment behavior like in Dotcom and OG (or) what drives customers to shop with us again ?\cb1 \
\cb3 \'a0\cb1 \
\pard\pardeftab720\partightenfactor0

\b \cf2 \cb3 Desired output:
\b0 \cb1 \
\pard\pardeftab720\partightenfactor0
\cf2 \cb3 -
\fs18\fsmilli9333 \'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0\'a0 
\fs26 Well commented Jupyter notebook (or) R Markdown\
\
\pard\pardeftab720\partightenfactor0

\b \cf2 Glossary:
\b0 \cb1 \

\itap1\trowd \taflags1 \trgaph108\trleft-108 \trbrdrt\brdrnil \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalt \clshdrawnil \clwWidth3349\clftsWidth3 \clbrdrt\brdrs\brdrw20\brdrcf4 \clbrdrl\brdrs\brdrw20\brdrcf4 \clbrdrb\brdrs\brdrw20\brdrcf4 \clbrdrr\brdrs\brdrw20\brdrcf4 \clpadl144 \clpadr144 \gaph\cellx4320
\clvertalt \clshdrawnil \clwWidth9117\clftsWidth3 \clbrdrt\brdrs\brdrw20\brdrcf4 \clbrdrl\brdrnil \clbrdrb\brdrs\brdrw20\brdrcf4 \clbrdrr\brdrs\brdrw20\brdrcf4 \clpadl144 \clpadr144 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0

\f2 \cf2 \cb3 Customer_id\cb1 \cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf2 \cb3 Customer identifier\cb1 \cell \row

\itap1\trowd \taflags1 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalt \clshdrawnil \clwWidth3349\clftsWidth3 \clbrdrt\brdrnil \clbrdrl\brdrs\brdrw20\brdrcf4 \clbrdrb\brdrs\brdrw20\brdrcf4 \clbrdrr\brdrs\brdrw20\brdrcf4 \clpadl144 \clpadr144 \gaph\cellx4320
\clvertalt \clshdrawnil \clwWidth9117\clftsWidth3 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrs\brdrw20\brdrcf4 \clbrdrr\brdrs\brdrw20\brdrcf4 \clpadl144 \clpadr144 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf2 \cb3 Order_date\cb1 \cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf2 \cb3 Order place date\cb1 \cell \row

\itap1\trowd \taflags1 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalt \clshdrawnil \clwWidth3349\clftsWidth3 \clbrdrt\brdrnil \clbrdrl\brdrs\brdrw20\brdrcf4 \clbrdrb\brdrs\brdrw20\brdrcf4 \clbrdrr\brdrs\brdrw20\brdrcf4 \clpadl144 \clpadr144 \gaph\cellx4320
\clvertalt \clshdrawnil \clwWidth9117\clftsWidth3 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrs\brdrw20\brdrcf4 \clbrdrr\brdrs\brdrw20\brdrcf4 \clpadl144 \clpadr144 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf2 \cb3 Shopping_medium\cb1 \cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf2 \cb3 Whether the order was placed in store or dotcom or through OG\cb1 \cell \row

\itap1\trowd \taflags1 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalt \clshdrawnil \clwWidth3349\clftsWidth3 \clbrdrt\brdrnil \clbrdrl\brdrs\brdrw20\brdrcf4 \clbrdrb\brdrs\brdrw20\brdrcf4 \clbrdrr\brdrs\brdrw20\brdrcf4 \clpadl144 \clpadr144 \gaph\cellx4320
\clvertalt \clshdrawnil \clwWidth9117\clftsWidth3 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrs\brdrw20\brdrcf4 \clbrdrr\brdrs\brdrw20\brdrcf4 \clpadl144 \clpadr144 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf2 \cb3 department\cb1 \cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf2 \cb3 Which department did customers shop in (only present for dotcom and OG)\cb1 \cell \row

\itap1\trowd \taflags1 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrt\brdrnil \trbrdrr\brdrnil 
\clvertalt \clshdrawnil \clwWidth3349\clftsWidth3 \clbrdrt\brdrnil \clbrdrl\brdrs\brdrw20\brdrcf4 \clbrdrb\brdrs\brdrw20\brdrcf4 \clbrdrr\brdrs\brdrw20\brdrcf4 \clpadl144 \clpadr144 \gaph\cellx4320
\clvertalt \clshdrawnil \clwWidth9117\clftsWidth3 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrs\brdrw20\brdrcf4 \clbrdrr\brdrs\brdrw20\brdrcf4 \clpadl144 \clpadr144 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf2 \cb3 sales\cb1 \cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf2 \cb3 Amount spent by the customer\cb1 \cell \lastrow\row
}