---
title: Changes in Female Participation over Time
author: Chris Fang & Hongtao Hao
---
<script type="text/javascript">
var figure23 =

vegaEmbed('#figure24', figure24);
</script>

As planned above, we started with a simple line graph displaying both male and female athletes’ percentage against all athletes. The strength of this method is that it is simple and clear. It shows that the female percentage has been steadily growing in the past century at the Olympics. The drawback is that it does not generate a stark contrast between male and female as a stacked bar chart can do. See Figure 21.

<div id="figure23" class="vis"></div>
<div class="caption">Figure 21: Line graph for changes in female participation</div>

We then used stacked bar graphs. We first tried stacking the bar horizontally with percentage on the x-axis and time on y-axis. See Figure 22.

<div id="figure24" class="vis"></div>
<div class="caption">Figure 22: Horizontal stacked bar chart for changes in female participation</div>

It was not as beautiful as we wanted, so we tried to put it upright and replace the axis labels. To highlight the trend, we set the male section grey and the female part bright blue. We also drew a red line at the intersection of the two parts. This time, female participation was obviously highlighted and the trend shown very clearly. See Figure 23.

<div id="figure25" class="vis"></div>
<div class="caption">Figure 23: Vertical stacked bar chart for changes in female participation</div>

However, as discussed above, stacked bar charts can only show the changes in percentages, not those in the actual number of participants. To also visualize how the total number of athletes participating in the Olympics changed over the century, we opted for a stacked area chart. See Figure 24.

<div id="figure26" class="vis"></div>
<div class="caption">Figure 24: Stacked area chart for changes in female participation</div>

The x-axis denotes time and the y-axis number of athletes. Areas are made up of male and female participants. The two added up to the total number of athletes. This stacked area chart not only shows the changes in female participation, it also displays how the total number of athletes has been increasing over the years. The drawback is that area is not a much preferred visual encoding. As a result, the comparison of percentages of male and female is not very accurate. That said, we think its strengths outweigh its disadvantages.

<script type="text/javascript">
var figure23 = {
  "$schema": "https://vega.github.io/schema/vega/v5.json",
  "background": "white",
  "padding": 5,
  "width": 700,
  "height": 300,
  "title": {
    "text": "Changes in female athletes participation in Summer Olympics (1896-2016)",
    "frame": "group"
  },
  "style": "cell",
  "data": [
    {"name": "selector017_store"},
    {
      "name": "data-acf04d5a8ed5b056492542ad6eb1d357",
      "values": [
        {
          "Unnamed: 0": 0,
          "Year": 1896,
          "Sex": "M",
          "Frequency": 380,
          "Percentage_decimal": 1,
          "Percentage": "100.0%"
        },
        {
          "Unnamed: 0": 1,
          "Year": 1896,
          "Sex": "F",
          "Frequency": 0,
          "Percentage_decimal": 0,
          "Percentage": "0.0%"
        },
        {
          "Unnamed: 0": 2,
          "Year": 1900,
          "Sex": "M",
          "Frequency": 1903,
          "Percentage_decimal": 0.983,
          "Percentage": "98.3%"
        },
        {
          "Unnamed: 0": 3,
          "Year": 1900,
          "Sex": "F",
          "Frequency": 33,
          "Percentage_decimal": 0.017,
          "Percentage": "1.7%"
        },
        {
          "Unnamed: 0": 4,
          "Year": 1904,
          "Sex": "M",
          "Frequency": 1285,
          "Percentage_decimal": 0.988,
          "Percentage": "98.8%"
        },
        {
          "Unnamed: 0": 5,
          "Year": 1904,
          "Sex": "F",
          "Frequency": 16,
          "Percentage_decimal": 0.012,
          "Percentage": "1.2%"
        },
        {
          "Unnamed: 0": 6,
          "Year": 1906,
          "Sex": "M",
          "Frequency": 1722,
          "Percentage_decimal": 0.9940000000000001,
          "Percentage": "99.4%"
        },
        {
          "Unnamed: 0": 7,
          "Year": 1906,
          "Sex": "F",
          "Frequency": 11,
          "Percentage_decimal": 0.006,
          "Percentage": "0.6%"
        },
        {
          "Unnamed: 0": 8,
          "Year": 1908,
          "Sex": "M",
          "Frequency": 3054,
          "Percentage_decimal": 0.985,
          "Percentage": "98.5%"
        },
        {
          "Unnamed: 0": 9,
          "Year": 1908,
          "Sex": "F",
          "Frequency": 47,
          "Percentage_decimal": 0.015,
          "Percentage": "1.5%"
        },
        {
          "Unnamed: 0": 10,
          "Year": 1912,
          "Sex": "M",
          "Frequency": 3953,
          "Percentage_decimal": 0.978,
          "Percentage": "97.8%"
        },
        {
          "Unnamed: 0": 11,
          "Year": 1912,
          "Sex": "F",
          "Frequency": 87,
          "Percentage_decimal": 0.022000000000000002,
          "Percentage": "2.2%"
        },
        {
          "Unnamed: 0": 12,
          "Year": 1920,
          "Sex": "M",
          "Frequency": 4158,
          "Percentage_decimal": 0.9690000000000001,
          "Percentage": "96.9%"
        },
        {
          "Unnamed: 0": 13,
          "Year": 1920,
          "Sex": "F",
          "Frequency": 134,
          "Percentage_decimal": 0.031,
          "Percentage": "3.1%"
        },
        {
          "Unnamed: 0": 14,
          "Year": 1924,
          "Sex": "M",
          "Frequency": 4989,
          "Percentage_decimal": 0.953,
          "Percentage": "95.3%"
        },
        {
          "Unnamed: 0": 15,
          "Year": 1924,
          "Sex": "F",
          "Frequency": 244,
          "Percentage_decimal": 0.047,
          "Percentage": "4.7%"
        },
        {
          "Unnamed: 0": 16,
          "Year": 1928,
          "Sex": "M",
          "Frequency": 4588,
          "Percentage_decimal": 0.919,
          "Percentage": "91.9%"
        },
        {
          "Unnamed: 0": 17,
          "Year": 1928,
          "Sex": "F",
          "Frequency": 404,
          "Percentage_decimal": 0.081,
          "Percentage": "8.1%"
        },
        {
          "Unnamed: 0": 18,
          "Year": 1932,
          "Sex": "M",
          "Frequency": 2622,
          "Percentage_decimal": 0.883,
          "Percentage": "88.3%"
        },
        {
          "Unnamed: 0": 19,
          "Year": 1932,
          "Sex": "F",
          "Frequency": 347,
          "Percentage_decimal": 0.11699999999999999,
          "Percentage": "11.7%"
        },
        {
          "Unnamed: 0": 20,
          "Year": 1936,
          "Sex": "M",
          "Frequency": 6038,
          "Percentage_decimal": 0.9279999999999999,
          "Percentage": "92.8%"
        },
        {
          "Unnamed: 0": 21,
          "Year": 1936,
          "Sex": "F",
          "Frequency": 468,
          "Percentage_decimal": 0.07200000000000001,
          "Percentage": "7.2%"
        },
        {
          "Unnamed: 0": 22,
          "Year": 1948,
          "Sex": "M",
          "Frequency": 5777,
          "Percentage_decimal": 0.902,
          "Percentage": "90.2%"
        },
        {
          "Unnamed: 0": 23,
          "Year": 1948,
          "Sex": "F",
          "Frequency": 628,
          "Percentage_decimal": 0.098,
          "Percentage": "9.8%"
        },
        {
          "Unnamed: 0": 24,
          "Year": 1952,
          "Sex": "M",
          "Frequency": 6773,
          "Percentage_decimal": 0.8190000000000001,
          "Percentage": "81.9%"
        },
        {
          "Unnamed: 0": 25,
          "Year": 1952,
          "Sex": "F",
          "Frequency": 1497,
          "Percentage_decimal": 0.18100000000000002,
          "Percentage": "18.1%"
        },
        {
          "Unnamed: 0": 26,
          "Year": 1956,
          "Sex": "M",
          "Frequency": 4234,
          "Percentage_decimal": 0.826,
          "Percentage": "82.6%"
        },
        {
          "Unnamed: 0": 27,
          "Year": 1956,
          "Sex": "F",
          "Frequency": 893,
          "Percentage_decimal": 0.174,
          "Percentage": "17.4%"
        },
        {
          "Unnamed: 0": 28,
          "Year": 1960,
          "Sex": "M",
          "Frequency": 6684,
          "Percentage_decimal": 0.823,
          "Percentage": "82.3%"
        },
        {
          "Unnamed: 0": 29,
          "Year": 1960,
          "Sex": "F",
          "Frequency": 1435,
          "Percentage_decimal": 0.177,
          "Percentage": "17.7%"
        },
        {
          "Unnamed: 0": 30,
          "Year": 1964,
          "Sex": "M",
          "Frequency": 6354,
          "Percentage_decimal": 0.825,
          "Percentage": "82.5%"
        },
        {
          "Unnamed: 0": 31,
          "Year": 1964,
          "Sex": "F",
          "Frequency": 1348,
          "Percentage_decimal": 0.175,
          "Percentage": "17.5%"
        },
        {
          "Unnamed: 0": 32,
          "Year": 1968,
          "Sex": "M",
          "Frequency": 6811,
          "Percentage_decimal": 0.7929999999999999,
          "Percentage": "79.3%"
        },
        {
          "Unnamed: 0": 33,
          "Year": 1968,
          "Sex": "F",
          "Frequency": 1777,
          "Percentage_decimal": 0.207,
          "Percentage": "20.7%"
        },
        {
          "Unnamed: 0": 34,
          "Year": 1972,
          "Sex": "M",
          "Frequency": 8111,
          "Percentage_decimal": 0.787,
          "Percentage": "78.7%"
        },
        {
          "Unnamed: 0": 35,
          "Year": 1972,
          "Sex": "F",
          "Frequency": 2193,
          "Percentage_decimal": 0.213,
          "Percentage": "21.3%"
        },
        {
          "Unnamed: 0": 36,
          "Year": 1976,
          "Sex": "M",
          "Frequency": 6469,
          "Percentage_decimal": 0.7490000000000001,
          "Percentage": "74.9%"
        },
        {
          "Unnamed: 0": 37,
          "Year": 1976,
          "Sex": "F",
          "Frequency": 2172,
          "Percentage_decimal": 0.251,
          "Percentage": "25.1%"
        },
        {
          "Unnamed: 0": 38,
          "Year": 1980,
          "Sex": "M",
          "Frequency": 5435,
          "Percentage_decimal": 0.7559999999999999,
          "Percentage": "75.6%"
        },
        {
          "Unnamed: 0": 39,
          "Year": 1980,
          "Sex": "F",
          "Frequency": 1756,
          "Percentage_decimal": 0.244,
          "Percentage": "24.4%"
        },
        {
          "Unnamed: 0": 40,
          "Year": 1984,
          "Sex": "M",
          "Frequency": 7007,
          "Percentage_decimal": 0.741,
          "Percentage": "74.1%"
        },
        {
          "Unnamed: 0": 41,
          "Year": 1984,
          "Sex": "F",
          "Frequency": 2447,
          "Percentage_decimal": 0.259,
          "Percentage": "25.9%"
        },
        {
          "Unnamed: 0": 42,
          "Year": 1988,
          "Sex": "M",
          "Frequency": 8494,
          "Percentage_decimal": 0.706,
          "Percentage": "70.6%"
        },
        {
          "Unnamed: 0": 43,
          "Year": 1988,
          "Sex": "F",
          "Frequency": 3543,
          "Percentage_decimal": 0.294,
          "Percentage": "29.4%"
        },
        {
          "Unnamed: 0": 44,
          "Year": 1992,
          "Sex": "M",
          "Frequency": 8853,
          "Percentage_decimal": 0.682,
          "Percentage": "68.2%"
        },
        {
          "Unnamed: 0": 45,
          "Year": 1992,
          "Sex": "F",
          "Frequency": 4124,
          "Percentage_decimal": 0.318,
          "Percentage": "31.8%"
        },
        {
          "Unnamed: 0": 46,
          "Year": 1996,
          "Sex": "M",
          "Frequency": 8772,
          "Percentage_decimal": 0.637,
          "Percentage": "63.7%"
        },
        {
          "Unnamed: 0": 47,
          "Year": 1996,
          "Sex": "F",
          "Frequency": 5008,
          "Percentage_decimal": 0.363,
          "Percentage": "36.3%"
        },
        {
          "Unnamed: 0": 48,
          "Year": 2000,
          "Sex": "M",
          "Frequency": 8390,
          "Percentage_decimal": 0.607,
          "Percentage": "60.7%"
        },
        {
          "Unnamed: 0": 49,
          "Year": 2000,
          "Sex": "F",
          "Frequency": 5431,
          "Percentage_decimal": 0.39299999999999996,
          "Percentage": "39.3%"
        },
        {
          "Unnamed: 0": 50,
          "Year": 2004,
          "Sex": "M",
          "Frequency": 7897,
          "Percentage_decimal": 0.5870000000000001,
          "Percentage": "58.7%"
        },
        {
          "Unnamed: 0": 51,
          "Year": 2004,
          "Sex": "F",
          "Frequency": 5546,
          "Percentage_decimal": 0.413,
          "Percentage": "41.3%"
        },
        {
          "Unnamed: 0": 52,
          "Year": 2008,
          "Sex": "M",
          "Frequency": 7786,
          "Percentage_decimal": 0.5720000000000001,
          "Percentage": "57.2%"
        },
        {
          "Unnamed: 0": 53,
          "Year": 2008,
          "Sex": "F",
          "Frequency": 5816,
          "Percentage_decimal": 0.428,
          "Percentage": "42.8%"
        },
        {
          "Unnamed: 0": 54,
          "Year": 2012,
          "Sex": "M",
          "Frequency": 7105,
          "Percentage_decimal": 0.55,
          "Percentage": "55.0%"
        },
        {
          "Unnamed: 0": 55,
          "Year": 2012,
          "Sex": "F",
          "Frequency": 5815,
          "Percentage_decimal": 0.45,
          "Percentage": "45.0%"
        },
        {
          "Unnamed: 0": 56,
          "Year": 2016,
          "Sex": "M",
          "Frequency": 7465,
          "Percentage_decimal": 0.545,
          "Percentage": "54.5%"
        },
        {
          "Unnamed: 0": 57,
          "Year": 2016,
          "Sex": "F",
          "Frequency": 6223,
          "Percentage_decimal": 0.455,
          "Percentage": "45.5%"
        }
      ]
    },
    {
      "name": "data_0",
      "source": "data-acf04d5a8ed5b056492542ad6eb1d357",
      "transform": [
        {"type": "formula", "expr": "toNumber(datum[\"Year\"])", "as": "Year"}
      ]
    }
  ],
  "signals": [
    {
      "name": "unit",
      "value": {},
      "on": [
        {"events": "mousemove", "update": "isTuple(group()) ? group() : unit"}
      ]
    },
    {
      "name": "selector017",
      "update": "vlSelectionResolve(\"selector017_store\", \"union\")"
    },
    {
      "name": "selector017_Year",
      "on": [
        {
          "events": {"signal": "selector017_translate_delta"},
          "update": "panLinear(selector017_translate_anchor.extent_x, -selector017_translate_delta.x / width)"
        },
        {
          "events": {"signal": "selector017_zoom_delta"},
          "update": "zoomLinear(domain(\"x\"), selector017_zoom_anchor.x, selector017_zoom_delta)"
        },
        {"events": [{"source": "scope", "type": "dblclick"}], "update": "null"}
      ]
    },
    {
      "name": "selector017_Percentage_decimal",
      "on": [
        {
          "events": {"signal": "selector017_translate_delta"},
          "update": "panLinear(selector017_translate_anchor.extent_y, selector017_translate_delta.y / height)"
        },
        {
          "events": {"signal": "selector017_zoom_delta"},
          "update": "zoomLinear(domain(\"y\"), selector017_zoom_anchor.y, selector017_zoom_delta)"
        },
        {"events": [{"source": "scope", "type": "dblclick"}], "update": "null"}
      ]
    },
    {
      "name": "selector017_tuple",
      "on": [
        {
          "events": [
            {"signal": "selector017_Year || selector017_Percentage_decimal"}
          ],
          "update": "selector017_Year && selector017_Percentage_decimal ? {unit: \"\", fields: selector017_tuple_fields, values: [selector017_Year,selector017_Percentage_decimal]} : null"
        }
      ]
    },
    {
      "name": "selector017_tuple_fields",
      "value": [
        {"field": "Year", "channel": "x", "type": "R"},
        {"field": "Percentage_decimal", "channel": "y", "type": "R"}
      ]
    },
    {
      "name": "selector017_translate_anchor",
      "value": {},
      "on": [
        {
          "events": [{"source": "scope", "type": "mousedown"}],
          "update": "{x: x(unit), y: y(unit), extent_x: domain(\"x\"), extent_y: domain(\"y\")}"
        }
      ]
    },
    {
      "name": "selector017_translate_delta",
      "value": {},
      "on": [
        {
          "events": [
            {
              "source": "window",
              "type": "mousemove",
              "consume": true,
              "between": [
                {"source": "scope", "type": "mousedown"},
                {"source": "window", "type": "mouseup"}
              ]
            }
          ],
          "update": "{x: selector017_translate_anchor.x - x(unit), y: selector017_translate_anchor.y - y(unit)}"
        }
      ]
    },
    {
      "name": "selector017_zoom_anchor",
      "on": [
        {
          "events": [{"source": "scope", "type": "wheel", "consume": true}],
          "update": "{x: invert(\"x\", x(unit)), y: invert(\"y\", y(unit))}"
        }
      ]
    },
    {
      "name": "selector017_zoom_delta",
      "on": [
        {
          "events": [{"source": "scope", "type": "wheel", "consume": true}],
          "force": true,
          "update": "pow(1.001, event.deltaY * pow(16, event.deltaMode))"
        }
      ]
    },
    {
      "name": "selector017_modify",
      "on": [
        {
          "events": {"signal": "selector017_tuple"},
          "update": "modify(\"selector017_store\", selector017_tuple, true)"
        }
      ]
    }
  ],
  "marks": [
    {
      "name": "pathgroup",
      "type": "group",
      "from": {
        "facet": {
          "name": "faceted_path_main",
          "data": "data_0",
          "groupby": ["Sex"]
        }
      },
      "encode": {
        "update": {
          "width": {"field": {"group": "width"}},
          "height": {"field": {"group": "height"}}
        }
      },
      "marks": [
        {
          "name": "marks",
          "type": "line",
          "clip": true,
          "style": ["line"],
          "sort": {"field": "datum[\"Year\"]"},
          "interactive": true,
          "from": {"data": "faceted_path_main"},
          "encode": {
            "update": {
              "stroke": {"scale": "color", "field": "Sex"},
              "tooltip": {
                "signal": "{\"Year\": format(datum[\"Year\"], \"\"), \"Sex\": isValid(datum[\"Sex\"]) ? datum[\"Sex\"] : \"\"+datum[\"Sex\"], \"Percentage\": isValid(datum[\"Percentage\"]) ? datum[\"Percentage\"] : \"\"+datum[\"Percentage\"]}"
              },
              "description": {
                "signal": "\"Sex\" + \": \" + (isValid(datum[\"Sex\"]) ? datum[\"Sex\"] : \"\"+datum[\"Sex\"]) + \"; \" + \"Year\" + \": \" + (format(datum[\"Year\"], \"\")) + \"; \" + \"Percentage\" + \": \" + (format(datum[\"Percentage_decimal\"], \"%\"))"
              },
              "x": {"scale": "x", "field": "Year"},
              "y": {"scale": "y", "field": "Percentage_decimal"},
              "strokeWidth": {"value": 5},
              "defined": {
                "signal": "isValid(datum[\"Year\"]) && isFinite(+datum[\"Year\"]) && isValid(datum[\"Percentage_decimal\"]) && isFinite(+datum[\"Percentage_decimal\"])"
              }
            }
          }
        }
      ]
    }
  ],
  "scales": [
    {
      "name": "x",
      "type": "linear",
      "domain": {"data": "data_0", "field": "Year"},
      "domainRaw": {"signal": "selector017[\"Year\"]"},
      "range": [0, {"signal": "width"}],
      "nice": true,
      "zero": false
    },
    {
      "name": "y",
      "type": "linear",
      "domain": {"data": "data_0", "field": "Percentage_decimal"},
      "domainRaw": {"signal": "selector017[\"Percentage_decimal\"]"},
      "range": [{"signal": "height"}, 0],
      "nice": true,
      "zero": true
    },
    {
      "name": "color",
      "type": "ordinal",
      "domain": {"data": "data_0", "field": "Sex", "sort": true},
      "range": "category"
    }
  ],
  "axes": [
    {
      "scale": "x",
      "orient": "bottom",
      "gridScale": "y",
      "grid": true,
      "tickCount": {"signal": "ceil(width/40)"},
      "domain": false,
      "labels": false,
      "aria": false,
      "maxExtent": 0,
      "minExtent": 0,
      "ticks": false,
      "zindex": 0
    },
    {
      "scale": "y",
      "orient": "left",
      "gridScale": "x",
      "grid": true,
      "tickCount": {"signal": "ceil(height/40)"},
      "domain": false,
      "labels": false,
      "aria": false,
      "maxExtent": 0,
      "minExtent": 0,
      "ticks": false,
      "zindex": 0
    },
    {
      "scale": "x",
      "orient": "bottom",
      "grid": false,
      "title": "Year",
      "labelFlush": true,
      "labelOverlap": true,
      "tickCount": {"signal": "ceil(width/40)"},
      "zindex": 0
    },
    {
      "scale": "y",
      "orient": "left",
      "grid": false,
      "title": "Percentage",
      "format": "%",
      "labelOverlap": true,
      "tickCount": {"signal": "ceil(height/40)"},
      "zindex": 0
    }
  ],
  "legends": [{"stroke": "color", "symbolType": "stroke", "title": "Sex"}],
  "config": {
    "legend": {
      "cornerRadius": 10,
      "fillColor": "#EEEEEE",
      "labelFontSize": 14,
      "padding": 10,
      "strokeColor": "gray"
    },
    "style": {"group-title": {"fontSize": 16}},
    "axis": {"labelFontSize": 12, "titleFontSize": 14}
  }
};
      vegaEmbed('#figure23', figure23);
</script>

<script type="text/javascript">
var figure24 = {
  "$schema": "https://vega.github.io/schema/vega/v5.json",
  "background": "white",
  "padding": 5,
  "width": 700,
  "height": 300,
  "title": {
    "text": "Changes in female athletes participation in Summer Olympics (1896-2016)",
    "frame": "group"
  },
  "style": "cell",
  "data": [
    {"name": "selector018_store"},
    {
      "name": "data-acf04d5a8ed5b056492542ad6eb1d357",
      "values": [
        {
          "Unnamed: 0": 0,
          "Year": 1896,
          "Sex": "M",
          "Frequency": 380,
          "Percentage_decimal": 1,
          "Percentage": "100.0%"
        },
        {
          "Unnamed: 0": 1,
          "Year": 1896,
          "Sex": "F",
          "Frequency": 0,
          "Percentage_decimal": 0,
          "Percentage": "0.0%"
        },
        {
          "Unnamed: 0": 2,
          "Year": 1900,
          "Sex": "M",
          "Frequency": 1903,
          "Percentage_decimal": 0.983,
          "Percentage": "98.3%"
        },
        {
          "Unnamed: 0": 3,
          "Year": 1900,
          "Sex": "F",
          "Frequency": 33,
          "Percentage_decimal": 0.017,
          "Percentage": "1.7%"
        },
        {
          "Unnamed: 0": 4,
          "Year": 1904,
          "Sex": "M",
          "Frequency": 1285,
          "Percentage_decimal": 0.988,
          "Percentage": "98.8%"
        },
        {
          "Unnamed: 0": 5,
          "Year": 1904,
          "Sex": "F",
          "Frequency": 16,
          "Percentage_decimal": 0.012,
          "Percentage": "1.2%"
        },
        {
          "Unnamed: 0": 6,
          "Year": 1906,
          "Sex": "M",
          "Frequency": 1722,
          "Percentage_decimal": 0.9940000000000001,
          "Percentage": "99.4%"
        },
        {
          "Unnamed: 0": 7,
          "Year": 1906,
          "Sex": "F",
          "Frequency": 11,
          "Percentage_decimal": 0.006,
          "Percentage": "0.6%"
        },
        {
          "Unnamed: 0": 8,
          "Year": 1908,
          "Sex": "M",
          "Frequency": 3054,
          "Percentage_decimal": 0.985,
          "Percentage": "98.5%"
        },
        {
          "Unnamed: 0": 9,
          "Year": 1908,
          "Sex": "F",
          "Frequency": 47,
          "Percentage_decimal": 0.015,
          "Percentage": "1.5%"
        },
        {
          "Unnamed: 0": 10,
          "Year": 1912,
          "Sex": "M",
          "Frequency": 3953,
          "Percentage_decimal": 0.978,
          "Percentage": "97.8%"
        },
        {
          "Unnamed: 0": 11,
          "Year": 1912,
          "Sex": "F",
          "Frequency": 87,
          "Percentage_decimal": 0.022000000000000002,
          "Percentage": "2.2%"
        },
        {
          "Unnamed: 0": 12,
          "Year": 1920,
          "Sex": "M",
          "Frequency": 4158,
          "Percentage_decimal": 0.9690000000000001,
          "Percentage": "96.9%"
        },
        {
          "Unnamed: 0": 13,
          "Year": 1920,
          "Sex": "F",
          "Frequency": 134,
          "Percentage_decimal": 0.031,
          "Percentage": "3.1%"
        },
        {
          "Unnamed: 0": 14,
          "Year": 1924,
          "Sex": "M",
          "Frequency": 4989,
          "Percentage_decimal": 0.953,
          "Percentage": "95.3%"
        },
        {
          "Unnamed: 0": 15,
          "Year": 1924,
          "Sex": "F",
          "Frequency": 244,
          "Percentage_decimal": 0.047,
          "Percentage": "4.7%"
        },
        {
          "Unnamed: 0": 16,
          "Year": 1928,
          "Sex": "M",
          "Frequency": 4588,
          "Percentage_decimal": 0.919,
          "Percentage": "91.9%"
        },
        {
          "Unnamed: 0": 17,
          "Year": 1928,
          "Sex": "F",
          "Frequency": 404,
          "Percentage_decimal": 0.081,
          "Percentage": "8.1%"
        },
        {
          "Unnamed: 0": 18,
          "Year": 1932,
          "Sex": "M",
          "Frequency": 2622,
          "Percentage_decimal": 0.883,
          "Percentage": "88.3%"
        },
        {
          "Unnamed: 0": 19,
          "Year": 1932,
          "Sex": "F",
          "Frequency": 347,
          "Percentage_decimal": 0.11699999999999999,
          "Percentage": "11.7%"
        },
        {
          "Unnamed: 0": 20,
          "Year": 1936,
          "Sex": "M",
          "Frequency": 6038,
          "Percentage_decimal": 0.9279999999999999,
          "Percentage": "92.8%"
        },
        {
          "Unnamed: 0": 21,
          "Year": 1936,
          "Sex": "F",
          "Frequency": 468,
          "Percentage_decimal": 0.07200000000000001,
          "Percentage": "7.2%"
        },
        {
          "Unnamed: 0": 22,
          "Year": 1948,
          "Sex": "M",
          "Frequency": 5777,
          "Percentage_decimal": 0.902,
          "Percentage": "90.2%"
        },
        {
          "Unnamed: 0": 23,
          "Year": 1948,
          "Sex": "F",
          "Frequency": 628,
          "Percentage_decimal": 0.098,
          "Percentage": "9.8%"
        },
        {
          "Unnamed: 0": 24,
          "Year": 1952,
          "Sex": "M",
          "Frequency": 6773,
          "Percentage_decimal": 0.8190000000000001,
          "Percentage": "81.9%"
        },
        {
          "Unnamed: 0": 25,
          "Year": 1952,
          "Sex": "F",
          "Frequency": 1497,
          "Percentage_decimal": 0.18100000000000002,
          "Percentage": "18.1%"
        },
        {
          "Unnamed: 0": 26,
          "Year": 1956,
          "Sex": "M",
          "Frequency": 4234,
          "Percentage_decimal": 0.826,
          "Percentage": "82.6%"
        },
        {
          "Unnamed: 0": 27,
          "Year": 1956,
          "Sex": "F",
          "Frequency": 893,
          "Percentage_decimal": 0.174,
          "Percentage": "17.4%"
        },
        {
          "Unnamed: 0": 28,
          "Year": 1960,
          "Sex": "M",
          "Frequency": 6684,
          "Percentage_decimal": 0.823,
          "Percentage": "82.3%"
        },
        {
          "Unnamed: 0": 29,
          "Year": 1960,
          "Sex": "F",
          "Frequency": 1435,
          "Percentage_decimal": 0.177,
          "Percentage": "17.7%"
        },
        {
          "Unnamed: 0": 30,
          "Year": 1964,
          "Sex": "M",
          "Frequency": 6354,
          "Percentage_decimal": 0.825,
          "Percentage": "82.5%"
        },
        {
          "Unnamed: 0": 31,
          "Year": 1964,
          "Sex": "F",
          "Frequency": 1348,
          "Percentage_decimal": 0.175,
          "Percentage": "17.5%"
        },
        {
          "Unnamed: 0": 32,
          "Year": 1968,
          "Sex": "M",
          "Frequency": 6811,
          "Percentage_decimal": 0.7929999999999999,
          "Percentage": "79.3%"
        },
        {
          "Unnamed: 0": 33,
          "Year": 1968,
          "Sex": "F",
          "Frequency": 1777,
          "Percentage_decimal": 0.207,
          "Percentage": "20.7%"
        },
        {
          "Unnamed: 0": 34,
          "Year": 1972,
          "Sex": "M",
          "Frequency": 8111,
          "Percentage_decimal": 0.787,
          "Percentage": "78.7%"
        },
        {
          "Unnamed: 0": 35,
          "Year": 1972,
          "Sex": "F",
          "Frequency": 2193,
          "Percentage_decimal": 0.213,
          "Percentage": "21.3%"
        },
        {
          "Unnamed: 0": 36,
          "Year": 1976,
          "Sex": "M",
          "Frequency": 6469,
          "Percentage_decimal": 0.7490000000000001,
          "Percentage": "74.9%"
        },
        {
          "Unnamed: 0": 37,
          "Year": 1976,
          "Sex": "F",
          "Frequency": 2172,
          "Percentage_decimal": 0.251,
          "Percentage": "25.1%"
        },
        {
          "Unnamed: 0": 38,
          "Year": 1980,
          "Sex": "M",
          "Frequency": 5435,
          "Percentage_decimal": 0.7559999999999999,
          "Percentage": "75.6%"
        },
        {
          "Unnamed: 0": 39,
          "Year": 1980,
          "Sex": "F",
          "Frequency": 1756,
          "Percentage_decimal": 0.244,
          "Percentage": "24.4%"
        },
        {
          "Unnamed: 0": 40,
          "Year": 1984,
          "Sex": "M",
          "Frequency": 7007,
          "Percentage_decimal": 0.741,
          "Percentage": "74.1%"
        },
        {
          "Unnamed: 0": 41,
          "Year": 1984,
          "Sex": "F",
          "Frequency": 2447,
          "Percentage_decimal": 0.259,
          "Percentage": "25.9%"
        },
        {
          "Unnamed: 0": 42,
          "Year": 1988,
          "Sex": "M",
          "Frequency": 8494,
          "Percentage_decimal": 0.706,
          "Percentage": "70.6%"
        },
        {
          "Unnamed: 0": 43,
          "Year": 1988,
          "Sex": "F",
          "Frequency": 3543,
          "Percentage_decimal": 0.294,
          "Percentage": "29.4%"
        },
        {
          "Unnamed: 0": 44,
          "Year": 1992,
          "Sex": "M",
          "Frequency": 8853,
          "Percentage_decimal": 0.682,
          "Percentage": "68.2%"
        },
        {
          "Unnamed: 0": 45,
          "Year": 1992,
          "Sex": "F",
          "Frequency": 4124,
          "Percentage_decimal": 0.318,
          "Percentage": "31.8%"
        },
        {
          "Unnamed: 0": 46,
          "Year": 1996,
          "Sex": "M",
          "Frequency": 8772,
          "Percentage_decimal": 0.637,
          "Percentage": "63.7%"
        },
        {
          "Unnamed: 0": 47,
          "Year": 1996,
          "Sex": "F",
          "Frequency": 5008,
          "Percentage_decimal": 0.363,
          "Percentage": "36.3%"
        },
        {
          "Unnamed: 0": 48,
          "Year": 2000,
          "Sex": "M",
          "Frequency": 8390,
          "Percentage_decimal": 0.607,
          "Percentage": "60.7%"
        },
        {
          "Unnamed: 0": 49,
          "Year": 2000,
          "Sex": "F",
          "Frequency": 5431,
          "Percentage_decimal": 0.39299999999999996,
          "Percentage": "39.3%"
        },
        {
          "Unnamed: 0": 50,
          "Year": 2004,
          "Sex": "M",
          "Frequency": 7897,
          "Percentage_decimal": 0.5870000000000001,
          "Percentage": "58.7%"
        },
        {
          "Unnamed: 0": 51,
          "Year": 2004,
          "Sex": "F",
          "Frequency": 5546,
          "Percentage_decimal": 0.413,
          "Percentage": "41.3%"
        },
        {
          "Unnamed: 0": 52,
          "Year": 2008,
          "Sex": "M",
          "Frequency": 7786,
          "Percentage_decimal": 0.5720000000000001,
          "Percentage": "57.2%"
        },
        {
          "Unnamed: 0": 53,
          "Year": 2008,
          "Sex": "F",
          "Frequency": 5816,
          "Percentage_decimal": 0.428,
          "Percentage": "42.8%"
        },
        {
          "Unnamed: 0": 54,
          "Year": 2012,
          "Sex": "M",
          "Frequency": 7105,
          "Percentage_decimal": 0.55,
          "Percentage": "55.0%"
        },
        {
          "Unnamed: 0": 55,
          "Year": 2012,
          "Sex": "F",
          "Frequency": 5815,
          "Percentage_decimal": 0.45,
          "Percentage": "45.0%"
        },
        {
          "Unnamed: 0": 56,
          "Year": 2016,
          "Sex": "M",
          "Frequency": 7465,
          "Percentage_decimal": 0.545,
          "Percentage": "54.5%"
        },
        {
          "Unnamed: 0": 57,
          "Year": 2016,
          "Sex": "F",
          "Frequency": 6223,
          "Percentage_decimal": 0.455,
          "Percentage": "45.5%"
        }
      ]
    },
    {
      "name": "data_0",
      "source": "data-acf04d5a8ed5b056492542ad6eb1d357",
      "transform": [
        {
          "type": "aggregate",
          "groupby": ["Sex", "Year", "Percentage"],
          "ops": ["sum"],
          "fields": ["Frequency"],
          "as": ["sum_Frequency"]
        },
        {
          "type": "stack",
          "groupby": ["Year"],
          "field": "sum_Frequency",
          "sort": {"field": ["Sex"], "order": ["ascending"]},
          "as": ["sum_Frequency_start", "sum_Frequency_end"],
          "offset": "normalize"
        },
        {
          "type": "filter",
          "expr": "isValid(datum[\"sum_Frequency\"]) && isFinite(+datum[\"sum_Frequency\"]) && isValid(datum[\"Year\"]) && isFinite(+datum[\"Year\"])"
        }
      ]
    }
  ],
  "signals": [
    {
      "name": "unit",
      "value": {},
      "on": [
        {"events": "mousemove", "update": "isTuple(group()) ? group() : unit"}
      ]
    },
    {
      "name": "selector018",
      "update": "vlSelectionResolve(\"selector018_store\", \"union\")"
    },
    {
      "name": "selector018_Year",
      "on": [
        {
          "events": {"signal": "selector018_translate_delta"},
          "update": "panLinear(selector018_translate_anchor.extent_y, selector018_translate_delta.y / height)"
        },
        {
          "events": {"signal": "selector018_zoom_delta"},
          "update": "zoomLinear(domain(\"y\"), selector018_zoom_anchor.y, selector018_zoom_delta)"
        },
        {"events": [{"source": "scope", "type": "dblclick"}], "update": "null"}
      ]
    },
    {
      "name": "selector018_tuple",
      "on": [
        {
          "events": [{"signal": "selector018_Year"}],
          "update": "selector018_Year ? {unit: \"\", fields: selector018_tuple_fields, values: [selector018_Year]} : null"
        }
      ]
    },
    {
      "name": "selector018_tuple_fields",
      "value": [{"field": "Year", "channel": "y", "type": "R"}]
    },
    {
      "name": "selector018_translate_anchor",
      "value": {},
      "on": [
        {
          "events": [{"source": "scope", "type": "mousedown"}],
          "update": "{x: x(unit), y: y(unit), extent_y: domain(\"y\")}"
        }
      ]
    },
    {
      "name": "selector018_translate_delta",
      "value": {},
      "on": [
        {
          "events": [
            {
              "source": "window",
              "type": "mousemove",
              "consume": true,
              "between": [
                {"source": "scope", "type": "mousedown"},
                {"source": "window", "type": "mouseup"}
              ]
            }
          ],
          "update": "{x: selector018_translate_anchor.x - x(unit), y: selector018_translate_anchor.y - y(unit)}"
        }
      ]
    },
    {
      "name": "selector018_zoom_anchor",
      "on": [
        {
          "events": [{"source": "scope", "type": "wheel", "consume": true}],
          "update": "{x: invert(\"x\", x(unit)), y: invert(\"y\", y(unit))}"
        }
      ]
    },
    {
      "name": "selector018_zoom_delta",
      "on": [
        {
          "events": [{"source": "scope", "type": "wheel", "consume": true}],
          "force": true,
          "update": "pow(1.001, event.deltaY * pow(16, event.deltaMode))"
        }
      ]
    },
    {
      "name": "selector018_modify",
      "on": [
        {
          "events": {"signal": "selector018_tuple"},
          "update": "modify(\"selector018_store\", selector018_tuple, true)"
        }
      ]
    }
  ],
  "marks": [
    {
      "name": "marks",
      "type": "rect",
      "clip": true,
      "style": ["bar"],
      "interactive": true,
      "from": {"data": "data_0"},
      "encode": {
        "update": {
          "fill": {"scale": "color", "field": "Sex"},
          "tooltip": {
            "signal": "{\"Year\": format(datum[\"Year\"], \"\"), \"Sex\": isValid(datum[\"Sex\"]) ? datum[\"Sex\"] : \"\"+datum[\"Sex\"], \"Percentage\": isValid(datum[\"Percentage\"]) ? datum[\"Percentage\"] : \"\"+datum[\"Percentage\"]}"
          },
          "ariaRoleDescription": {"value": "bar"},
          "description": {
            "signal": "\"Sex\" + \": \" + (isValid(datum[\"Sex\"]) ? datum[\"Sex\"] : \"\"+datum[\"Sex\"]) + \"; \" + \"Year\" + \": \" + (format(datum[\"Year\"], \"\")) + \"; \" + \"Percentage\" + \": \" + (format(datum[\"sum_Frequency_end\"]-datum[\"sum_Frequency_start\"], \"%\"))"
          },
          "x": {"scale": "x", "field": "sum_Frequency_end"},
          "x2": {"scale": "x", "field": "sum_Frequency_start"},
          "yc": [
            {
              "test": "!isValid(datum[\"Year\"]) || !isFinite(+datum[\"Year\"])",
              "field": {"group": "height"}
            },
            {"scale": "y", "field": "Year"}
          ],
          "height": {"value": 4}
        }
      }
    }
  ],
  "scales": [
    {
      "name": "x",
      "type": "linear",
      "domain": [0, 1],
      "range": [0, {"signal": "width"}],
      "nice": true,
      "zero": true
    },
    {
      "name": "y",
      "type": "linear",
      "domain": {"data": "data_0", "field": "Year"},
      "domainRaw": {"signal": "selector018[\"Year\"]"},
      "range": [{"signal": "height"}, 0],
      "nice": true,
      "zero": false,
      "padding": 5
    },
    {
      "name": "color",
      "type": "ordinal",
      "domain": {"data": "data_0", "field": "Sex", "sort": true},
      "range": "category"
    }
  ],
  "axes": [
    {
      "scale": "y",
      "orient": "left",
      "gridScale": "x",
      "grid": true,
      "tickCount": {"signal": "ceil(height/40)"},
      "domain": false,
      "labels": false,
      "aria": false,
      "maxExtent": 0,
      "minExtent": 0,
      "ticks": false,
      "zindex": 0
    },
    {
      "scale": "x",
      "orient": "bottom",
      "grid": false,
      "title": "Percentage",
      "format": "%",
      "labelFlush": true,
      "labelOverlap": true,
      "tickCount": {"signal": "ceil(width/40)"},
      "zindex": 0
    },
    {
      "scale": "y",
      "orient": "left",
      "grid": false,
      "title": "Year",
      "labelOverlap": true,
      "tickCount": {"signal": "ceil(height/40)"},
      "zindex": 0
    }
  ],
  "legends": [{"fill": "color", "symbolType": "square", "title": "Sex"}],
  "config": {
    "legend": {
      "cornerRadius": 10,
      "fillColor": "#EEEEEE",
      "labelFontSize": 14,
      "padding": 10,
      "strokeColor": "gray"
    },
    "style": {"group-title": {"fontSize": 16}},
    "axis": {"labelFontSize": 14, "titleFontSize": 16}
  }
};
      vegaEmbed('#figure24', figure24);
</script>

<script type="text/javascript">
var figure25 = {
  "$schema": "https://vega.github.io/schema/vega/v5.json",
  "background": "white",
  "padding": 5,
  "width": 700,
  "height": 300,
  "title": {
    "text": "Changes in female athletes participation in Summer Olympics (1896-2016)",
    "frame": "group"
  },
  "style": "cell",
  "data": [
    {
      "name": "data-acf04d5a8ed5b056492542ad6eb1d357",
      "values": [
        {
          "Unnamed: 0": 0,
          "Year": 1896,
          "Sex": "M",
          "Frequency": 380,
          "Percentage_decimal": 1,
          "Percentage": "100.0%"
        },
        {
          "Unnamed: 0": 1,
          "Year": 1896,
          "Sex": "F",
          "Frequency": 0,
          "Percentage_decimal": 0,
          "Percentage": "0.0%"
        },
        {
          "Unnamed: 0": 2,
          "Year": 1900,
          "Sex": "M",
          "Frequency": 1903,
          "Percentage_decimal": 0.983,
          "Percentage": "98.3%"
        },
        {
          "Unnamed: 0": 3,
          "Year": 1900,
          "Sex": "F",
          "Frequency": 33,
          "Percentage_decimal": 0.017,
          "Percentage": "1.7%"
        },
        {
          "Unnamed: 0": 4,
          "Year": 1904,
          "Sex": "M",
          "Frequency": 1285,
          "Percentage_decimal": 0.988,
          "Percentage": "98.8%"
        },
        {
          "Unnamed: 0": 5,
          "Year": 1904,
          "Sex": "F",
          "Frequency": 16,
          "Percentage_decimal": 0.012,
          "Percentage": "1.2%"
        },
        {
          "Unnamed: 0": 6,
          "Year": 1906,
          "Sex": "M",
          "Frequency": 1722,
          "Percentage_decimal": 0.9940000000000001,
          "Percentage": "99.4%"
        },
        {
          "Unnamed: 0": 7,
          "Year": 1906,
          "Sex": "F",
          "Frequency": 11,
          "Percentage_decimal": 0.006,
          "Percentage": "0.6%"
        },
        {
          "Unnamed: 0": 8,
          "Year": 1908,
          "Sex": "M",
          "Frequency": 3054,
          "Percentage_decimal": 0.985,
          "Percentage": "98.5%"
        },
        {
          "Unnamed: 0": 9,
          "Year": 1908,
          "Sex": "F",
          "Frequency": 47,
          "Percentage_decimal": 0.015,
          "Percentage": "1.5%"
        },
        {
          "Unnamed: 0": 10,
          "Year": 1912,
          "Sex": "M",
          "Frequency": 3953,
          "Percentage_decimal": 0.978,
          "Percentage": "97.8%"
        },
        {
          "Unnamed: 0": 11,
          "Year": 1912,
          "Sex": "F",
          "Frequency": 87,
          "Percentage_decimal": 0.022000000000000002,
          "Percentage": "2.2%"
        },
        {
          "Unnamed: 0": 12,
          "Year": 1920,
          "Sex": "M",
          "Frequency": 4158,
          "Percentage_decimal": 0.9690000000000001,
          "Percentage": "96.9%"
        },
        {
          "Unnamed: 0": 13,
          "Year": 1920,
          "Sex": "F",
          "Frequency": 134,
          "Percentage_decimal": 0.031,
          "Percentage": "3.1%"
        },
        {
          "Unnamed: 0": 14,
          "Year": 1924,
          "Sex": "M",
          "Frequency": 4989,
          "Percentage_decimal": 0.953,
          "Percentage": "95.3%"
        },
        {
          "Unnamed: 0": 15,
          "Year": 1924,
          "Sex": "F",
          "Frequency": 244,
          "Percentage_decimal": 0.047,
          "Percentage": "4.7%"
        },
        {
          "Unnamed: 0": 16,
          "Year": 1928,
          "Sex": "M",
          "Frequency": 4588,
          "Percentage_decimal": 0.919,
          "Percentage": "91.9%"
        },
        {
          "Unnamed: 0": 17,
          "Year": 1928,
          "Sex": "F",
          "Frequency": 404,
          "Percentage_decimal": 0.081,
          "Percentage": "8.1%"
        },
        {
          "Unnamed: 0": 18,
          "Year": 1932,
          "Sex": "M",
          "Frequency": 2622,
          "Percentage_decimal": 0.883,
          "Percentage": "88.3%"
        },
        {
          "Unnamed: 0": 19,
          "Year": 1932,
          "Sex": "F",
          "Frequency": 347,
          "Percentage_decimal": 0.11699999999999999,
          "Percentage": "11.7%"
        },
        {
          "Unnamed: 0": 20,
          "Year": 1936,
          "Sex": "M",
          "Frequency": 6038,
          "Percentage_decimal": 0.9279999999999999,
          "Percentage": "92.8%"
        },
        {
          "Unnamed: 0": 21,
          "Year": 1936,
          "Sex": "F",
          "Frequency": 468,
          "Percentage_decimal": 0.07200000000000001,
          "Percentage": "7.2%"
        },
        {
          "Unnamed: 0": 22,
          "Year": 1948,
          "Sex": "M",
          "Frequency": 5777,
          "Percentage_decimal": 0.902,
          "Percentage": "90.2%"
        },
        {
          "Unnamed: 0": 23,
          "Year": 1948,
          "Sex": "F",
          "Frequency": 628,
          "Percentage_decimal": 0.098,
          "Percentage": "9.8%"
        },
        {
          "Unnamed: 0": 24,
          "Year": 1952,
          "Sex": "M",
          "Frequency": 6773,
          "Percentage_decimal": 0.8190000000000001,
          "Percentage": "81.9%"
        },
        {
          "Unnamed: 0": 25,
          "Year": 1952,
          "Sex": "F",
          "Frequency": 1497,
          "Percentage_decimal": 0.18100000000000002,
          "Percentage": "18.1%"
        },
        {
          "Unnamed: 0": 26,
          "Year": 1956,
          "Sex": "M",
          "Frequency": 4234,
          "Percentage_decimal": 0.826,
          "Percentage": "82.6%"
        },
        {
          "Unnamed: 0": 27,
          "Year": 1956,
          "Sex": "F",
          "Frequency": 893,
          "Percentage_decimal": 0.174,
          "Percentage": "17.4%"
        },
        {
          "Unnamed: 0": 28,
          "Year": 1960,
          "Sex": "M",
          "Frequency": 6684,
          "Percentage_decimal": 0.823,
          "Percentage": "82.3%"
        },
        {
          "Unnamed: 0": 29,
          "Year": 1960,
          "Sex": "F",
          "Frequency": 1435,
          "Percentage_decimal": 0.177,
          "Percentage": "17.7%"
        },
        {
          "Unnamed: 0": 30,
          "Year": 1964,
          "Sex": "M",
          "Frequency": 6354,
          "Percentage_decimal": 0.825,
          "Percentage": "82.5%"
        },
        {
          "Unnamed: 0": 31,
          "Year": 1964,
          "Sex": "F",
          "Frequency": 1348,
          "Percentage_decimal": 0.175,
          "Percentage": "17.5%"
        },
        {
          "Unnamed: 0": 32,
          "Year": 1968,
          "Sex": "M",
          "Frequency": 6811,
          "Percentage_decimal": 0.7929999999999999,
          "Percentage": "79.3%"
        },
        {
          "Unnamed: 0": 33,
          "Year": 1968,
          "Sex": "F",
          "Frequency": 1777,
          "Percentage_decimal": 0.207,
          "Percentage": "20.7%"
        },
        {
          "Unnamed: 0": 34,
          "Year": 1972,
          "Sex": "M",
          "Frequency": 8111,
          "Percentage_decimal": 0.787,
          "Percentage": "78.7%"
        },
        {
          "Unnamed: 0": 35,
          "Year": 1972,
          "Sex": "F",
          "Frequency": 2193,
          "Percentage_decimal": 0.213,
          "Percentage": "21.3%"
        },
        {
          "Unnamed: 0": 36,
          "Year": 1976,
          "Sex": "M",
          "Frequency": 6469,
          "Percentage_decimal": 0.7490000000000001,
          "Percentage": "74.9%"
        },
        {
          "Unnamed: 0": 37,
          "Year": 1976,
          "Sex": "F",
          "Frequency": 2172,
          "Percentage_decimal": 0.251,
          "Percentage": "25.1%"
        },
        {
          "Unnamed: 0": 38,
          "Year": 1980,
          "Sex": "M",
          "Frequency": 5435,
          "Percentage_decimal": 0.7559999999999999,
          "Percentage": "75.6%"
        },
        {
          "Unnamed: 0": 39,
          "Year": 1980,
          "Sex": "F",
          "Frequency": 1756,
          "Percentage_decimal": 0.244,
          "Percentage": "24.4%"
        },
        {
          "Unnamed: 0": 40,
          "Year": 1984,
          "Sex": "M",
          "Frequency": 7007,
          "Percentage_decimal": 0.741,
          "Percentage": "74.1%"
        },
        {
          "Unnamed: 0": 41,
          "Year": 1984,
          "Sex": "F",
          "Frequency": 2447,
          "Percentage_decimal": 0.259,
          "Percentage": "25.9%"
        },
        {
          "Unnamed: 0": 42,
          "Year": 1988,
          "Sex": "M",
          "Frequency": 8494,
          "Percentage_decimal": 0.706,
          "Percentage": "70.6%"
        },
        {
          "Unnamed: 0": 43,
          "Year": 1988,
          "Sex": "F",
          "Frequency": 3543,
          "Percentage_decimal": 0.294,
          "Percentage": "29.4%"
        },
        {
          "Unnamed: 0": 44,
          "Year": 1992,
          "Sex": "M",
          "Frequency": 8853,
          "Percentage_decimal": 0.682,
          "Percentage": "68.2%"
        },
        {
          "Unnamed: 0": 45,
          "Year": 1992,
          "Sex": "F",
          "Frequency": 4124,
          "Percentage_decimal": 0.318,
          "Percentage": "31.8%"
        },
        {
          "Unnamed: 0": 46,
          "Year": 1996,
          "Sex": "M",
          "Frequency": 8772,
          "Percentage_decimal": 0.637,
          "Percentage": "63.7%"
        },
        {
          "Unnamed: 0": 47,
          "Year": 1996,
          "Sex": "F",
          "Frequency": 5008,
          "Percentage_decimal": 0.363,
          "Percentage": "36.3%"
        },
        {
          "Unnamed: 0": 48,
          "Year": 2000,
          "Sex": "M",
          "Frequency": 8390,
          "Percentage_decimal": 0.607,
          "Percentage": "60.7%"
        },
        {
          "Unnamed: 0": 49,
          "Year": 2000,
          "Sex": "F",
          "Frequency": 5431,
          "Percentage_decimal": 0.39299999999999996,
          "Percentage": "39.3%"
        },
        {
          "Unnamed: 0": 50,
          "Year": 2004,
          "Sex": "M",
          "Frequency": 7897,
          "Percentage_decimal": 0.5870000000000001,
          "Percentage": "58.7%"
        },
        {
          "Unnamed: 0": 51,
          "Year": 2004,
          "Sex": "F",
          "Frequency": 5546,
          "Percentage_decimal": 0.413,
          "Percentage": "41.3%"
        },
        {
          "Unnamed: 0": 52,
          "Year": 2008,
          "Sex": "M",
          "Frequency": 7786,
          "Percentage_decimal": 0.5720000000000001,
          "Percentage": "57.2%"
        },
        {
          "Unnamed: 0": 53,
          "Year": 2008,
          "Sex": "F",
          "Frequency": 5816,
          "Percentage_decimal": 0.428,
          "Percentage": "42.8%"
        },
        {
          "Unnamed: 0": 54,
          "Year": 2012,
          "Sex": "M",
          "Frequency": 7105,
          "Percentage_decimal": 0.55,
          "Percentage": "55.0%"
        },
        {
          "Unnamed: 0": 55,
          "Year": 2012,
          "Sex": "F",
          "Frequency": 5815,
          "Percentage_decimal": 0.45,
          "Percentage": "45.0%"
        },
        {
          "Unnamed: 0": 56,
          "Year": 2016,
          "Sex": "M",
          "Frequency": 7465,
          "Percentage_decimal": 0.545,
          "Percentage": "54.5%"
        },
        {
          "Unnamed: 0": 57,
          "Year": 2016,
          "Sex": "F",
          "Frequency": 6223,
          "Percentage_decimal": 0.455,
          "Percentage": "45.5%"
        }
      ]
    },
    {
      "name": "data-4be4e5362f7ec640992a51633fcaf211",
      "values": [
        {
          "Unnamed: 0": 1,
          "Year": 1896,
          "Sex": "F",
          "Frequency": 0,
          "Percentage_decimal": 0,
          "Percentage": "0.0%"
        },
        {
          "Unnamed: 0": 3,
          "Year": 1900,
          "Sex": "F",
          "Frequency": 33,
          "Percentage_decimal": 0.017,
          "Percentage": "1.7%"
        },
        {
          "Unnamed: 0": 5,
          "Year": 1904,
          "Sex": "F",
          "Frequency": 16,
          "Percentage_decimal": 0.012,
          "Percentage": "1.2%"
        },
        {
          "Unnamed: 0": 7,
          "Year": 1906,
          "Sex": "F",
          "Frequency": 11,
          "Percentage_decimal": 0.006,
          "Percentage": "0.6%"
        },
        {
          "Unnamed: 0": 9,
          "Year": 1908,
          "Sex": "F",
          "Frequency": 47,
          "Percentage_decimal": 0.015,
          "Percentage": "1.5%"
        },
        {
          "Unnamed: 0": 11,
          "Year": 1912,
          "Sex": "F",
          "Frequency": 87,
          "Percentage_decimal": 0.022000000000000002,
          "Percentage": "2.2%"
        },
        {
          "Unnamed: 0": 13,
          "Year": 1920,
          "Sex": "F",
          "Frequency": 134,
          "Percentage_decimal": 0.031,
          "Percentage": "3.1%"
        },
        {
          "Unnamed: 0": 15,
          "Year": 1924,
          "Sex": "F",
          "Frequency": 244,
          "Percentage_decimal": 0.047,
          "Percentage": "4.7%"
        },
        {
          "Unnamed: 0": 17,
          "Year": 1928,
          "Sex": "F",
          "Frequency": 404,
          "Percentage_decimal": 0.081,
          "Percentage": "8.1%"
        },
        {
          "Unnamed: 0": 19,
          "Year": 1932,
          "Sex": "F",
          "Frequency": 347,
          "Percentage_decimal": 0.11699999999999999,
          "Percentage": "11.7%"
        },
        {
          "Unnamed: 0": 21,
          "Year": 1936,
          "Sex": "F",
          "Frequency": 468,
          "Percentage_decimal": 0.07200000000000001,
          "Percentage": "7.2%"
        },
        {
          "Unnamed: 0": 23,
          "Year": 1948,
          "Sex": "F",
          "Frequency": 628,
          "Percentage_decimal": 0.098,
          "Percentage": "9.8%"
        },
        {
          "Unnamed: 0": 25,
          "Year": 1952,
          "Sex": "F",
          "Frequency": 1497,
          "Percentage_decimal": 0.18100000000000002,
          "Percentage": "18.1%"
        },
        {
          "Unnamed: 0": 27,
          "Year": 1956,
          "Sex": "F",
          "Frequency": 893,
          "Percentage_decimal": 0.174,
          "Percentage": "17.4%"
        },
        {
          "Unnamed: 0": 29,
          "Year": 1960,
          "Sex": "F",
          "Frequency": 1435,
          "Percentage_decimal": 0.177,
          "Percentage": "17.7%"
        },
        {
          "Unnamed: 0": 31,
          "Year": 1964,
          "Sex": "F",
          "Frequency": 1348,
          "Percentage_decimal": 0.175,
          "Percentage": "17.5%"
        },
        {
          "Unnamed: 0": 33,
          "Year": 1968,
          "Sex": "F",
          "Frequency": 1777,
          "Percentage_decimal": 0.207,
          "Percentage": "20.7%"
        },
        {
          "Unnamed: 0": 35,
          "Year": 1972,
          "Sex": "F",
          "Frequency": 2193,
          "Percentage_decimal": 0.213,
          "Percentage": "21.3%"
        },
        {
          "Unnamed: 0": 37,
          "Year": 1976,
          "Sex": "F",
          "Frequency": 2172,
          "Percentage_decimal": 0.251,
          "Percentage": "25.1%"
        },
        {
          "Unnamed: 0": 39,
          "Year": 1980,
          "Sex": "F",
          "Frequency": 1756,
          "Percentage_decimal": 0.244,
          "Percentage": "24.4%"
        },
        {
          "Unnamed: 0": 41,
          "Year": 1984,
          "Sex": "F",
          "Frequency": 2447,
          "Percentage_decimal": 0.259,
          "Percentage": "25.9%"
        },
        {
          "Unnamed: 0": 43,
          "Year": 1988,
          "Sex": "F",
          "Frequency": 3543,
          "Percentage_decimal": 0.294,
          "Percentage": "29.4%"
        },
        {
          "Unnamed: 0": 45,
          "Year": 1992,
          "Sex": "F",
          "Frequency": 4124,
          "Percentage_decimal": 0.318,
          "Percentage": "31.8%"
        },
        {
          "Unnamed: 0": 47,
          "Year": 1996,
          "Sex": "F",
          "Frequency": 5008,
          "Percentage_decimal": 0.363,
          "Percentage": "36.3%"
        },
        {
          "Unnamed: 0": 49,
          "Year": 2000,
          "Sex": "F",
          "Frequency": 5431,
          "Percentage_decimal": 0.39299999999999996,
          "Percentage": "39.3%"
        },
        {
          "Unnamed: 0": 51,
          "Year": 2004,
          "Sex": "F",
          "Frequency": 5546,
          "Percentage_decimal": 0.413,
          "Percentage": "41.3%"
        },
        {
          "Unnamed: 0": 53,
          "Year": 2008,
          "Sex": "F",
          "Frequency": 5816,
          "Percentage_decimal": 0.428,
          "Percentage": "42.8%"
        },
        {
          "Unnamed: 0": 55,
          "Year": 2012,
          "Sex": "F",
          "Frequency": 5815,
          "Percentage_decimal": 0.45,
          "Percentage": "45.0%"
        },
        {
          "Unnamed: 0": 57,
          "Year": 2016,
          "Sex": "F",
          "Frequency": 6223,
          "Percentage_decimal": 0.455,
          "Percentage": "45.5%"
        }
      ]
    },
    {
      "name": "data_0",
      "source": "data-acf04d5a8ed5b056492542ad6eb1d357",
      "transform": [
        {
          "type": "aggregate",
          "groupby": ["Sex", "Year", "Percentage"],
          "ops": ["sum"],
          "fields": ["Frequency"],
          "as": ["sum_Frequency"]
        },
        {
          "type": "stack",
          "groupby": ["Year"],
          "field": "sum_Frequency",
          "sort": {"field": ["Sex"], "order": ["ascending"]},
          "as": ["sum_Frequency_start", "sum_Frequency_end"],
          "offset": "normalize"
        },
        {
          "type": "filter",
          "expr": "isValid(datum[\"Year\"]) && isFinite(+datum[\"Year\"]) && isValid(datum[\"sum_Frequency\"]) && isFinite(+datum[\"sum_Frequency\"])"
        }
      ]
    },
    {
      "name": "data_1",
      "source": "data-4be4e5362f7ec640992a51633fcaf211",
      "transform": [
        {"type": "formula", "expr": "toNumber(datum[\"Year\"])", "as": "Year"}
      ]
    },
    {
      "name": "data_2",
      "source": "data_1",
      "transform": [
        {
          "type": "filter",
          "expr": "isValid(datum[\"Year\"]) && isFinite(+datum[\"Year\"]) && isValid(datum[\"Percentage_decimal\"]) && isFinite(+datum[\"Percentage_decimal\"])"
        }
      ]
    }
  ],
  "marks": [
    {
      "name": "layer_0_layer_0_marks",
      "type": "rect",
      "style": ["bar"],
      "from": {"data": "data_0"},
      "encode": {
        "update": {
          "fill": {"scale": "color", "field": "Sex"},
          "tooltip": {
            "signal": "{\"Year\": format(datum[\"Year\"], \"\"), \"Sex\": isValid(datum[\"Sex\"]) ? datum[\"Sex\"] : \"\"+datum[\"Sex\"], \"Percentage\": isValid(datum[\"Percentage\"]) ? datum[\"Percentage\"] : \"\"+datum[\"Percentage\"]}"
          },
          "ariaRoleDescription": {"value": "bar"},
          "description": {
            "signal": "\"Sex\" + \": \" + (isValid(datum[\"Sex\"]) ? datum[\"Sex\"] : \"\"+datum[\"Sex\"]) + \"; \" + \"Year\" + \": \" + (format(datum[\"Year\"], \"\")) + \"; \" + \"Percentage\" + \": \" + (format(datum[\"sum_Frequency_end\"]-datum[\"sum_Frequency_start\"], \"%\"))"
          },
          "xc": [
            {
              "test": "!isValid(datum[\"Year\"]) || !isFinite(+datum[\"Year\"])",
              "value": 0
            },
            {"scale": "x", "field": "Year"}
          ],
          "width": {"value": 10},
          "y": {"scale": "y", "field": "sum_Frequency_end"},
          "y2": {"scale": "y", "field": "sum_Frequency_start"}
        }
      }
    },
    {
      "name": "layer_0_layer_1_layer_0_marks",
      "type": "line",
      "style": ["line"],
      "sort": {"field": "datum[\"Year\"]"},
      "from": {"data": "data_1"},
      "encode": {
        "update": {
          "stroke": {"value": "red"},
          "description": {
            "signal": "\"Year\" + \": \" + (format(datum[\"Year\"], \"\")) + \"; \" + \"Percentage_decimal\" + \": \" + (format(datum[\"Percentage_decimal\"], \"\"))"
          },
          "x": {"scale": "x", "field": "Year"},
          "y": {"scale": "y", "field": "Percentage_decimal"},
          "defined": {
            "signal": "isValid(datum[\"Year\"]) && isFinite(+datum[\"Year\"]) && isValid(datum[\"Percentage_decimal\"]) && isFinite(+datum[\"Percentage_decimal\"])"
          }
        }
      }
    },
    {
      "name": "layer_0_layer_1_layer_1_marks",
      "type": "symbol",
      "style": ["point"],
      "from": {"data": "data_2"},
      "encode": {
        "update": {
          "opacity": {"value": 1},
          "fill": {"value": "#4c78a8"},
          "ariaRoleDescription": {"value": "point"},
          "description": {
            "signal": "\"Year\" + \": \" + (format(datum[\"Year\"], \"\")) + \"; \" + \"Percentage_decimal\" + \": \" + (format(datum[\"Percentage_decimal\"], \"\"))"
          },
          "x": [
            {
              "test": "!isValid(datum[\"Year\"]) || !isFinite(+datum[\"Year\"])",
              "value": 0
            },
            {"scale": "x", "field": "Year"}
          ],
          "y": {"scale": "y", "field": "Percentage_decimal"}
        }
      }
    }
  ],
  "scales": [
    {
      "name": "x",
      "type": "linear",
      "domain": {
        "fields": [
          {"data": "data_0", "field": "Year"},
          {"data": "data_1", "field": "Year"},
          {"data": "data_2", "field": "Year"}
        ]
      },
      "range": [0, {"signal": "width"}],
      "nice": true,
      "zero": false,
      "padding": 5
    },
    {
      "name": "y",
      "type": "linear",
      "domain": {
        "fields": [
          [0, 1],
          {"data": "data_1", "field": "Percentage_decimal"},
          {"data": "data_2", "field": "Percentage_decimal"}
        ]
      },
      "range": [{"signal": "height"}, 0],
      "nice": true,
      "zero": true
    },
    {
      "name": "color",
      "type": "ordinal",
      "domain": ["F", "M"],
      "range": ["blue", "grey"]
    }
  ],
  "axes": [
    {
      "scale": "x",
      "orient": "bottom",
      "gridScale": "y",
      "grid": true,
      "tickCount": {"signal": "ceil(width/40)"},
      "domain": false,
      "labels": false,
      "aria": false,
      "maxExtent": 0,
      "minExtent": 0,
      "ticks": false,
      "zindex": 0
    },
    {
      "scale": "x",
      "orient": "bottom",
      "grid": false,
      "title": "Year",
      "labelFlush": true,
      "labelOverlap": true,
      "tickCount": {"signal": "ceil(width/40)"},
      "zindex": 0
    },
    {
      "scale": "y",
      "orient": "left",
      "grid": false,
      "title": "Percentage",
      "format": "%",
      "labelOverlap": true,
      "tickCount": {"signal": "ceil(height/40)"},
      "zindex": 0
    }
  ],
  "legends": [{"fill": "color", "symbolType": "square", "title": "Sex"}],
  "config": {
    "legend": {
      "cornerRadius": 10,
      "fillColor": "#EEEEEE",
      "labelFontSize": 14,
      "padding": 10,
      "strokeColor": "gray"
    },
    "style": {"group-title": {"fontSize": 20}},
    "axis": {"labelFontSize": 14, "titleFontSize": 16}
  }
};
vegaEmbed('#figure25', figure25);
</script>

<script type="text/javascript">
var figure26 = {
  "$schema": "https://vega.github.io/schema/vega/v5.json",
  "background": "white",
  "padding": 5,
  "width": 700,
  "height": 300,
  "title": {
    "text": "Changes in female athletes participation in Summer Olympics (1896-2016)",
    "frame": "group"
  },
  "style": "cell",
  "data": [
    {"name": "selector019_store"},
    {
      "name": "data-acf04d5a8ed5b056492542ad6eb1d357",
      "values": [
        {
          "Unnamed: 0": 0,
          "Year": 1896,
          "Sex": "M",
          "Frequency": 380,
          "Percentage_decimal": 1,
          "Percentage": "100.0%"
        },
        {
          "Unnamed: 0": 1,
          "Year": 1896,
          "Sex": "F",
          "Frequency": 0,
          "Percentage_decimal": 0,
          "Percentage": "0.0%"
        },
        {
          "Unnamed: 0": 2,
          "Year": 1900,
          "Sex": "M",
          "Frequency": 1903,
          "Percentage_decimal": 0.983,
          "Percentage": "98.3%"
        },
        {
          "Unnamed: 0": 3,
          "Year": 1900,
          "Sex": "F",
          "Frequency": 33,
          "Percentage_decimal": 0.017,
          "Percentage": "1.7%"
        },
        {
          "Unnamed: 0": 4,
          "Year": 1904,
          "Sex": "M",
          "Frequency": 1285,
          "Percentage_decimal": 0.988,
          "Percentage": "98.8%"
        },
        {
          "Unnamed: 0": 5,
          "Year": 1904,
          "Sex": "F",
          "Frequency": 16,
          "Percentage_decimal": 0.012,
          "Percentage": "1.2%"
        },
        {
          "Unnamed: 0": 6,
          "Year": 1906,
          "Sex": "M",
          "Frequency": 1722,
          "Percentage_decimal": 0.9940000000000001,
          "Percentage": "99.4%"
        },
        {
          "Unnamed: 0": 7,
          "Year": 1906,
          "Sex": "F",
          "Frequency": 11,
          "Percentage_decimal": 0.006,
          "Percentage": "0.6%"
        },
        {
          "Unnamed: 0": 8,
          "Year": 1908,
          "Sex": "M",
          "Frequency": 3054,
          "Percentage_decimal": 0.985,
          "Percentage": "98.5%"
        },
        {
          "Unnamed: 0": 9,
          "Year": 1908,
          "Sex": "F",
          "Frequency": 47,
          "Percentage_decimal": 0.015,
          "Percentage": "1.5%"
        },
        {
          "Unnamed: 0": 10,
          "Year": 1912,
          "Sex": "M",
          "Frequency": 3953,
          "Percentage_decimal": 0.978,
          "Percentage": "97.8%"
        },
        {
          "Unnamed: 0": 11,
          "Year": 1912,
          "Sex": "F",
          "Frequency": 87,
          "Percentage_decimal": 0.022000000000000002,
          "Percentage": "2.2%"
        },
        {
          "Unnamed: 0": 12,
          "Year": 1920,
          "Sex": "M",
          "Frequency": 4158,
          "Percentage_decimal": 0.9690000000000001,
          "Percentage": "96.9%"
        },
        {
          "Unnamed: 0": 13,
          "Year": 1920,
          "Sex": "F",
          "Frequency": 134,
          "Percentage_decimal": 0.031,
          "Percentage": "3.1%"
        },
        {
          "Unnamed: 0": 14,
          "Year": 1924,
          "Sex": "M",
          "Frequency": 4989,
          "Percentage_decimal": 0.953,
          "Percentage": "95.3%"
        },
        {
          "Unnamed: 0": 15,
          "Year": 1924,
          "Sex": "F",
          "Frequency": 244,
          "Percentage_decimal": 0.047,
          "Percentage": "4.7%"
        },
        {
          "Unnamed: 0": 16,
          "Year": 1928,
          "Sex": "M",
          "Frequency": 4588,
          "Percentage_decimal": 0.919,
          "Percentage": "91.9%"
        },
        {
          "Unnamed: 0": 17,
          "Year": 1928,
          "Sex": "F",
          "Frequency": 404,
          "Percentage_decimal": 0.081,
          "Percentage": "8.1%"
        },
        {
          "Unnamed: 0": 18,
          "Year": 1932,
          "Sex": "M",
          "Frequency": 2622,
          "Percentage_decimal": 0.883,
          "Percentage": "88.3%"
        },
        {
          "Unnamed: 0": 19,
          "Year": 1932,
          "Sex": "F",
          "Frequency": 347,
          "Percentage_decimal": 0.11699999999999999,
          "Percentage": "11.7%"
        },
        {
          "Unnamed: 0": 20,
          "Year": 1936,
          "Sex": "M",
          "Frequency": 6038,
          "Percentage_decimal": 0.9279999999999999,
          "Percentage": "92.8%"
        },
        {
          "Unnamed: 0": 21,
          "Year": 1936,
          "Sex": "F",
          "Frequency": 468,
          "Percentage_decimal": 0.07200000000000001,
          "Percentage": "7.2%"
        },
        {
          "Unnamed: 0": 22,
          "Year": 1948,
          "Sex": "M",
          "Frequency": 5777,
          "Percentage_decimal": 0.902,
          "Percentage": "90.2%"
        },
        {
          "Unnamed: 0": 23,
          "Year": 1948,
          "Sex": "F",
          "Frequency": 628,
          "Percentage_decimal": 0.098,
          "Percentage": "9.8%"
        },
        {
          "Unnamed: 0": 24,
          "Year": 1952,
          "Sex": "M",
          "Frequency": 6773,
          "Percentage_decimal": 0.8190000000000001,
          "Percentage": "81.9%"
        },
        {
          "Unnamed: 0": 25,
          "Year": 1952,
          "Sex": "F",
          "Frequency": 1497,
          "Percentage_decimal": 0.18100000000000002,
          "Percentage": "18.1%"
        },
        {
          "Unnamed: 0": 26,
          "Year": 1956,
          "Sex": "M",
          "Frequency": 4234,
          "Percentage_decimal": 0.826,
          "Percentage": "82.6%"
        },
        {
          "Unnamed: 0": 27,
          "Year": 1956,
          "Sex": "F",
          "Frequency": 893,
          "Percentage_decimal": 0.174,
          "Percentage": "17.4%"
        },
        {
          "Unnamed: 0": 28,
          "Year": 1960,
          "Sex": "M",
          "Frequency": 6684,
          "Percentage_decimal": 0.823,
          "Percentage": "82.3%"
        },
        {
          "Unnamed: 0": 29,
          "Year": 1960,
          "Sex": "F",
          "Frequency": 1435,
          "Percentage_decimal": 0.177,
          "Percentage": "17.7%"
        },
        {
          "Unnamed: 0": 30,
          "Year": 1964,
          "Sex": "M",
          "Frequency": 6354,
          "Percentage_decimal": 0.825,
          "Percentage": "82.5%"
        },
        {
          "Unnamed: 0": 31,
          "Year": 1964,
          "Sex": "F",
          "Frequency": 1348,
          "Percentage_decimal": 0.175,
          "Percentage": "17.5%"
        },
        {
          "Unnamed: 0": 32,
          "Year": 1968,
          "Sex": "M",
          "Frequency": 6811,
          "Percentage_decimal": 0.7929999999999999,
          "Percentage": "79.3%"
        },
        {
          "Unnamed: 0": 33,
          "Year": 1968,
          "Sex": "F",
          "Frequency": 1777,
          "Percentage_decimal": 0.207,
          "Percentage": "20.7%"
        },
        {
          "Unnamed: 0": 34,
          "Year": 1972,
          "Sex": "M",
          "Frequency": 8111,
          "Percentage_decimal": 0.787,
          "Percentage": "78.7%"
        },
        {
          "Unnamed: 0": 35,
          "Year": 1972,
          "Sex": "F",
          "Frequency": 2193,
          "Percentage_decimal": 0.213,
          "Percentage": "21.3%"
        },
        {
          "Unnamed: 0": 36,
          "Year": 1976,
          "Sex": "M",
          "Frequency": 6469,
          "Percentage_decimal": 0.7490000000000001,
          "Percentage": "74.9%"
        },
        {
          "Unnamed: 0": 37,
          "Year": 1976,
          "Sex": "F",
          "Frequency": 2172,
          "Percentage_decimal": 0.251,
          "Percentage": "25.1%"
        },
        {
          "Unnamed: 0": 38,
          "Year": 1980,
          "Sex": "M",
          "Frequency": 5435,
          "Percentage_decimal": 0.7559999999999999,
          "Percentage": "75.6%"
        },
        {
          "Unnamed: 0": 39,
          "Year": 1980,
          "Sex": "F",
          "Frequency": 1756,
          "Percentage_decimal": 0.244,
          "Percentage": "24.4%"
        },
        {
          "Unnamed: 0": 40,
          "Year": 1984,
          "Sex": "M",
          "Frequency": 7007,
          "Percentage_decimal": 0.741,
          "Percentage": "74.1%"
        },
        {
          "Unnamed: 0": 41,
          "Year": 1984,
          "Sex": "F",
          "Frequency": 2447,
          "Percentage_decimal": 0.259,
          "Percentage": "25.9%"
        },
        {
          "Unnamed: 0": 42,
          "Year": 1988,
          "Sex": "M",
          "Frequency": 8494,
          "Percentage_decimal": 0.706,
          "Percentage": "70.6%"
        },
        {
          "Unnamed: 0": 43,
          "Year": 1988,
          "Sex": "F",
          "Frequency": 3543,
          "Percentage_decimal": 0.294,
          "Percentage": "29.4%"
        },
        {
          "Unnamed: 0": 44,
          "Year": 1992,
          "Sex": "M",
          "Frequency": 8853,
          "Percentage_decimal": 0.682,
          "Percentage": "68.2%"
        },
        {
          "Unnamed: 0": 45,
          "Year": 1992,
          "Sex": "F",
          "Frequency": 4124,
          "Percentage_decimal": 0.318,
          "Percentage": "31.8%"
        },
        {
          "Unnamed: 0": 46,
          "Year": 1996,
          "Sex": "M",
          "Frequency": 8772,
          "Percentage_decimal": 0.637,
          "Percentage": "63.7%"
        },
        {
          "Unnamed: 0": 47,
          "Year": 1996,
          "Sex": "F",
          "Frequency": 5008,
          "Percentage_decimal": 0.363,
          "Percentage": "36.3%"
        },
        {
          "Unnamed: 0": 48,
          "Year": 2000,
          "Sex": "M",
          "Frequency": 8390,
          "Percentage_decimal": 0.607,
          "Percentage": "60.7%"
        },
        {
          "Unnamed: 0": 49,
          "Year": 2000,
          "Sex": "F",
          "Frequency": 5431,
          "Percentage_decimal": 0.39299999999999996,
          "Percentage": "39.3%"
        },
        {
          "Unnamed: 0": 50,
          "Year": 2004,
          "Sex": "M",
          "Frequency": 7897,
          "Percentage_decimal": 0.5870000000000001,
          "Percentage": "58.7%"
        },
        {
          "Unnamed: 0": 51,
          "Year": 2004,
          "Sex": "F",
          "Frequency": 5546,
          "Percentage_decimal": 0.413,
          "Percentage": "41.3%"
        },
        {
          "Unnamed: 0": 52,
          "Year": 2008,
          "Sex": "M",
          "Frequency": 7786,
          "Percentage_decimal": 0.5720000000000001,
          "Percentage": "57.2%"
        },
        {
          "Unnamed: 0": 53,
          "Year": 2008,
          "Sex": "F",
          "Frequency": 5816,
          "Percentage_decimal": 0.428,
          "Percentage": "42.8%"
        },
        {
          "Unnamed: 0": 54,
          "Year": 2012,
          "Sex": "M",
          "Frequency": 7105,
          "Percentage_decimal": 0.55,
          "Percentage": "55.0%"
        },
        {
          "Unnamed: 0": 55,
          "Year": 2012,
          "Sex": "F",
          "Frequency": 5815,
          "Percentage_decimal": 0.45,
          "Percentage": "45.0%"
        },
        {
          "Unnamed: 0": 56,
          "Year": 2016,
          "Sex": "M",
          "Frequency": 7465,
          "Percentage_decimal": 0.545,
          "Percentage": "54.5%"
        },
        {
          "Unnamed: 0": 57,
          "Year": 2016,
          "Sex": "F",
          "Frequency": 6223,
          "Percentage_decimal": 0.455,
          "Percentage": "45.5%"
        }
      ]
    },
    {
      "name": "data_0",
      "source": "data-acf04d5a8ed5b056492542ad6eb1d357",
      "transform": [
        {"type": "formula", "expr": "toNumber(datum[\"Year\"])", "as": "Year"},
        {
          "type": "aggregate",
          "groupby": ["Sex", "Year", "Percentage"],
          "ops": ["sum"],
          "fields": ["Frequency"],
          "as": ["sum_Frequency"]
        },
        {
          "type": "impute",
          "field": "sum_Frequency",
          "groupby": ["Sex"],
          "key": "Year",
          "method": "value",
          "value": 0
        },
        {
          "type": "stack",
          "groupby": ["Year"],
          "field": "sum_Frequency",
          "sort": {"field": ["Sex"], "order": ["descending"]},
          "as": ["sum_Frequency_start", "sum_Frequency_end"],
          "offset": "zero"
        }
      ]
    }
  ],
  "signals": [
    {
      "name": "unit",
      "value": {},
      "on": [
        {"events": "mousemove", "update": "isTuple(group()) ? group() : unit"}
      ]
    },
    {
      "name": "selector019",
      "update": "vlSelectionResolve(\"selector019_store\", \"union\")"
    },
    {
      "name": "selector019_Year",
      "on": [
        {
          "events": {"signal": "selector019_translate_delta"},
          "update": "panLinear(selector019_translate_anchor.extent_x, -selector019_translate_delta.x / width)"
        },
        {
          "events": {"signal": "selector019_zoom_delta"},
          "update": "zoomLinear(domain(\"x\"), selector019_zoom_anchor.x, selector019_zoom_delta)"
        },
        {"events": [{"source": "scope", "type": "dblclick"}], "update": "null"}
      ]
    },
    {
      "name": "selector019_tuple",
      "on": [
        {
          "events": [{"signal": "selector019_Year"}],
          "update": "selector019_Year ? {unit: \"\", fields: selector019_tuple_fields, values: [selector019_Year]} : null"
        }
      ]
    },
    {
      "name": "selector019_tuple_fields",
      "value": [{"field": "Year", "channel": "x", "type": "R"}]
    },
    {
      "name": "selector019_translate_anchor",
      "value": {},
      "on": [
        {
          "events": [{"source": "scope", "type": "mousedown"}],
          "update": "{x: x(unit), y: y(unit), extent_x: domain(\"x\")}"
        }
      ]
    },
    {
      "name": "selector019_translate_delta",
      "value": {},
      "on": [
        {
          "events": [
            {
              "source": "window",
              "type": "mousemove",
              "consume": true,
              "between": [
                {"source": "scope", "type": "mousedown"},
                {"source": "window", "type": "mouseup"}
              ]
            }
          ],
          "update": "{x: selector019_translate_anchor.x - x(unit), y: selector019_translate_anchor.y - y(unit)}"
        }
      ]
    },
    {
      "name": "selector019_zoom_anchor",
      "on": [
        {
          "events": [{"source": "scope", "type": "wheel", "consume": true}],
          "update": "{x: invert(\"x\", x(unit)), y: invert(\"y\", y(unit))}"
        }
      ]
    },
    {
      "name": "selector019_zoom_delta",
      "on": [
        {
          "events": [{"source": "scope", "type": "wheel", "consume": true}],
          "force": true,
          "update": "pow(1.001, event.deltaY * pow(16, event.deltaMode))"
        }
      ]
    },
    {
      "name": "selector019_modify",
      "on": [
        {
          "events": {"signal": "selector019_tuple"},
          "update": "modify(\"selector019_store\", selector019_tuple, true)"
        }
      ]
    }
  ],
  "marks": [
    {
      "name": "pathgroup",
      "type": "group",
      "from": {
        "facet": {
          "name": "faceted_path_main",
          "data": "data_0",
          "groupby": ["Sex"]
        }
      },
      "encode": {
        "update": {
          "width": {"field": {"group": "width"}},
          "height": {"field": {"group": "height"}}
        }
      },
      "marks": [
        {
          "name": "marks",
          "type": "area",
          "clip": true,
          "style": ["area"],
          "sort": {"field": "datum[\"Year\"]"},
          "interactive": true,
          "from": {"data": "faceted_path_main"},
          "encode": {
            "update": {
              "orient": {"value": "vertical"},
              "fill": {"scale": "color", "field": "Sex"},
              "tooltip": {
                "signal": "{\"Year\": format(datum[\"Year\"], \"\"), \"Sex\": isValid(datum[\"Sex\"]) ? datum[\"Sex\"] : \"\"+datum[\"Sex\"], \"Percentage\": isValid(datum[\"Percentage\"]) ? datum[\"Percentage\"] : \"\"+datum[\"Percentage\"]}"
              },
              "description": {
                "signal": "\"Sex\" + \": \" + (isValid(datum[\"Sex\"]) ? datum[\"Sex\"] : \"\"+datum[\"Sex\"]) + \"; \" + \"Year\" + \": \" + (format(datum[\"Year\"], \"\")) + \"; \" + \"Percentage\" + \": \" + (isValid(datum[\"Percentage\"]) ? datum[\"Percentage\"] : \"\"+datum[\"Percentage\"]) + \"; \" + \"Sum of Frequency\" + \": \" + (format(datum[\"sum_Frequency\"], \"\"))"
              },
              "x": {"scale": "x", "field": "Year"},
              "y": {"scale": "y", "field": "sum_Frequency_end"},
              "y2": {"scale": "y", "field": "sum_Frequency_start"},
              "defined": {
                "signal": "isValid(datum[\"Year\"]) && isFinite(+datum[\"Year\"]) && isValid(datum[\"sum_Frequency\"]) && isFinite(+datum[\"sum_Frequency\"])"
              }
            }
          }
        }
      ]
    }
  ],
  "scales": [
    {
      "name": "x",
      "type": "linear",
      "domain": {"data": "data_0", "field": "Year"},
      "domainRaw": {"signal": "selector019[\"Year\"]"},
      "range": [0, {"signal": "width"}],
      "nice": true,
      "zero": false
    },
    {
      "name": "y",
      "type": "linear",
      "domain": {
        "data": "data_0",
        "fields": ["sum_Frequency_start", "sum_Frequency_end"]
      },
      "range": [{"signal": "height"}, 0],
      "nice": true,
      "zero": true
    },
    {
      "name": "color",
      "type": "ordinal",
      "domain": {"data": "data_0", "field": "Sex", "sort": true},
      "range": "category"
    }
  ],
  "axes": [
    {
      "scale": "x",
      "orient": "bottom",
      "gridScale": "y",
      "grid": true,
      "tickCount": {"signal": "ceil(width/40)"},
      "domain": false,
      "labels": false,
      "aria": false,
      "maxExtent": 0,
      "minExtent": 0,
      "ticks": false,
      "zindex": 0
    },
    {
      "scale": "y",
      "orient": "left",
      "gridScale": "x",
      "grid": true,
      "tickCount": {"signal": "ceil(height/40)"},
      "domain": false,
      "labels": false,
      "aria": false,
      "maxExtent": 0,
      "minExtent": 0,
      "ticks": false,
      "zindex": 0
    },
    {
      "scale": "x",
      "orient": "bottom",
      "grid": false,
      "title": "Year",
      "labelFlush": true,
      "labelOverlap": true,
      "tickCount": {"signal": "ceil(width/40)"},
      "zindex": 0
    },
    {
      "scale": "y",
      "orient": "left",
      "grid": false,
      "title": "Sum of Frequency",
      "labelOverlap": true,
      "tickCount": {"signal": "ceil(height/40)"},
      "zindex": 0
    }
  ],
  "legends": [{"fill": "color", "symbolType": "circle", "title": "Sex"}],
  "config": {
    "legend": {
      "cornerRadius": 10,
      "fillColor": "#EEEEEE",
      "labelFontSize": 14,
      "padding": 10,
      "strokeColor": "gray"
    },
    "style": {"group-title": {"fontSize": 16}},
    "axis": {"labelFontSize": 14, "titleFontSize": 16}
  }
};

vegaEmbed('#figure26', figure26);
</script>
