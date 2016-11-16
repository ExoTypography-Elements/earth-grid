<template>

<div class="et-grid">

   <slot></slot>
</div>

</template>
<script>

export default {
data () {
return {
msg: 'FINDBORG COOPERATION'
}
}
}
</script>
<style lang="stylus">
/*  Require ET Styles Framework */
 @import "../et/variables"
/*  End of ET Styles Framework */


/* GRID */
grid-desktop-columns = 12
grid-desktop-gutter = 16px
grid-desktop-margin = 16px
grid-desktop-breakpoint = 840px

grid-tablet-gutter = grid-desktop-gutter
grid-tablet-margin = grid-desktop-margin
grid-tablet-breakpoint = 480px

grid-phone-gutter = grid-desktop-gutter
grid-phone-margin = grid-desktop-margin
grid-cell-default-columns = grid-phone-columns
//Containers
.et-container
  margin: 0 auto
  padding: 0
//Vertical and Horizontal Layouts
//Flex Layout
.et-order-12
  -webkit-order: 12
  -ms-flex-order: 12
  order: 12
.et-order-11
  -webkit-order: 11
  -ms-flex-order: 11
  order: 11
.et-order-10
  -webkit-order: 10
  -ms-flex-order: 10
  order: 10
.et-order-9
  -webkit-order: 9
  -ms-flex-order: 9
  order: 9
.et-order-8
  -webkit-order: 8
  -ms-flex-order: 8
  order: 8
.et-order-7
  -webkit-order: 7
  -ms-flex-order: 7
  order: 7
.et-order-6
  -webkit-order: 6
  -ms-flex-order: 6
  order: 6
.et-order-5
  -webkit-order: 5
  -ms-flex-order: 5
  order: 5
.et-order-4
  -webkit-order: 4
  -ms-flex-order: 4
  order: 4
.et-order-3
  -webkit-order: 3
  -ms-flex-order: 3
  order: 3
.et-order-2
  -webkit-order: 2
  -ms-flex-order: 2
  order: 2
.et-order-1
  -webkit-order: 1
  -ms-flex-order: 1
  order: 1
.et-order-0
  -webkit-order: 0
  -ms-flex-order: 0
  order: 0

.et-grid {
    display: flex;
    flex-flow: row wrap;
    margin: 0 auto 0 auto;
    align-items: stretch;
}
.et-grid.et-grid-no-spacing {
    padding: 0;
}
.et-block {
    box-sizing: border-box;
}
.et-block-flex {
  flex-grow: 1;
  flex: 1;
}
.et-block-top {
    align-self: flex-start;
}
.et-block-middle {
    align-self: center;
}
.et-block-bottom {
    align-self: flex-end;
}
.et-block-stretch {
    align-self: stretch;
}
.et-grid.et-grid-nowrap{
  flex-wrap: nowrap;
}
.et-grid.et-grid-no-spacing>.et-block {
    margin: 0;
}
//Block Sizing

@media (max-width: 479px) {
    .et-grid {
    padding: 8px;
}
.et-block {
    margin: 8px;
    width: calc(100% - 16px);
}
.et-grid-no-spacing>.et-block {
    width: 100%}
.et-hide-sm {
    display: none !important;
}
.et-size-10, .et-size-sm-10.et-size-sm-10 {
    width: calc(10% - 16px);
}
.et-grid-no-spacing>.et-size-10, .et-grid-no-spacing>.et-size-sm-10.et-size-sm-10 {
    width: 10%}
.et-size-20, .et-size-sm-20.et-size-sm-20 {
    width: calc(20% - 16px);
}
.et-grid-no-spacing>.et-size-20, .et-grid-no-spacing>.et-size-sm-20.et-size-sm-20 {
    width: 20%}
.et-size-25, .et-size-sm-25.et-size-sm-25 {
    width: calc(25% - 16px);
}
.et-grid-no-spacing>.et-size-25, .et-grid-no-spacing>.et-size-sm-25.et-size-sm-25 {
    width: 25%}

.et-size-30, .et-size-sm-30.et-size-sm-30 {
    width: calc(30% - 16px);
}
.et-grid-no-spacing>.et-size-30, .et-grid-no-spacing>.et-size-sm-30.et-size-sm-30 {
    width: 30%}

.et-size-40, .et-size-sm-40.et-size-sm-40 {
  width: calc(40% - 16px);
}
.et-grid-no-spacing>.et-size-40, .et-grid-no-spacing>.et-size-sm-40.et-size-sm-40 {
    width: 40%}


.et-size-60, .et-size-sm-60.et-size-sm-60 {
  width: calc(60% - 16px);
}
.et-grid-no-spacing>.et-size-60, .et-grid-no-spacing>.et-size-sm-60.et-size-sm-60 {
    width: 60%}


.et-size-50, .et-size-sm-50.et-size-sm-50 {
    width: calc(50% - 16px);
}
.et-grid-no-spacing>.et-size-50, .et-grid-no-spacing>.et-size-sm-50.et-size-sm-50 {
    width: 50%}

.et-size-70, .et-size-sm-70.et-size-sm-70 {
    width: calc(70% - 16px);
}
.et-grid-no-spacing>.et-size-70, .et-grid-no-spacing>.et-size-sm-70.et-size-sm-70 {
    width: 70%}
.et-size-75, .et-size-sm-75.et-size-sm-75 {
    width: calc(75% - 16px);
}
.et-grid-no-spacing>.et-size-75, .et-grid-no-spacing>.et-size-sm-75.et-size-sm-50 {
    width: 75%}
.et-size-80, .et-size-sm-80.et-size-sm-80 {
    width: calc(80% - 16px);
}
.et-grid-no-spacing>.et-size-80, .et-grid-no-spacing>.et-size-sm-80.et-size-sm-80 {
    width: 80%}
.et-size-90, .et-size-sm-90.et-size-sm-90 {
    width: calc(90% - 16px);
}
.et-grid-no-spacing>.et-size-90, .et-grid-no-spacing>.et-size-sm-90.et-size-sm-90 {
    width: 90%}

.et-size-100, .et-size-sm-100.et-size-sm-100 {
    width: calc(100% - 16px);
}
.et-grid-no-spacing>.et-size-100, .et-grid-no-spacing>.et-size-sm-100.et-size-sm-100 {
    width: 100%}
.et-block--1-offset, .et-block--1-offset-sm.et-block--1-offset-sm {
    margin-left: calc(25% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--1-offset, .et-grid.et-grid-no-spacing>.et-block--1-offset-sm.et-block--1-offset-sm {
    margin-left: 25%}
.et-block--2-offset, .et-block--2-offset-sm.et-block--2-offset-sm {
    margin-left: calc(50% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--2-offset, .et-grid.et-grid-no-spacing>.et-block--2-offset-sm.et-block--2-offset-sm {
    margin-left: 50%}
.et-block--3-offset, .et-block--3-offset-sm.et-block--3-offset-sm {
    margin-left: calc(75% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--3-offset, .et-grid.et-grid-no-spacing>.et-block--3-offset-sm.et-block--3-offset-sm {
    margin-left: 75%}
}
@media (min-width: 480px) and (max-width: 839px) {
    .et-grid {
    padding: 8px;
}
.et-block {
    margin: 8px;
    width: calc(50% - 16px);
}
.et-grid-no-spacing>.et-block {
    width: 50%}
.et-hide-md {
    display: none !important;
}
.et-size-10, .et-size-md-10.et-size-md-10 {
    width: calc(10% - 16px);
}
.et-grid-no-spacing>.et-size-10, .et-grid-no-spacing>.et-size-md-10.et-size-md-10 {
    width: 10%}
.et-size-20, .et-size-md-20.et-size-md-20 {
    width: calc(20% - 16px);
}
.et-grid-no-spacing>.et-size-20, .et-grid-no-spacing>.et-size-md-20.et-size-md-20 {
    width: 20%}
.et-size-25, .et-size-md-25.et-size-md-25 {
    width: calc(25% - 16px);
}
.et-grid-no-spacing>.et-size-25, .et-grid-no-spacing>.et-size-md-25.et-size-md-25 {
    width: 25%}

.et-size-30, .et-size-md-30.et-size-md-30 {
    width: calc(30% - 16px);
}
.et-grid-no-spacing>.et-size-30, .et-grid-no-spacing>.et-size-md-30.et-size-md-30 {
    width: 30%}

.et-size-40, .et-size-md-40.et-size-md-40 {
  width: calc(40% - 16px);
}
.et-grid-no-spacing>.et-size-40, .et-grid-no-spacing>.et-size-md-40.et-size-md-40 {
    width: 40%}


.et-size-60, .et-size-md-60.et-size-md-60 {
  width: calc(60% - 16px);
}
.et-grid-no-spacing>.et-size-60, .et-grid-no-spacing>.et-size-md-60.et-size-md-60 {
    width: 60%}


.et-size-50, .et-size-md-50.et-size-md-50 {
    width: calc(50% - 16px);
}
.et-grid-no-spacing>.et-size-50, .et-grid-no-spacing>.et-size-md-50.et-size-md-50 {
    width: 50%}

.et-size-70, .et-size-md-70.et-size-md-70 {
    width: calc(70% - 16px);
}
.et-grid-no-spacing>.et-size-70, .et-grid-no-spacing>.et-size-md-70.et-size-md-70 {
    width: 70%}
.et-size-75, .et-size-md-75.et-size-md-75 {
    width: calc(75% - 16px);
}
.et-grid-no-spacing>.et-size-75, .et-grid-no-spacing>.et-size-md-75.et-size-md-50 {
    width: 75%}
.et-size-80, .et-size-md-80.et-size-md-80 {
    width: calc(80% - 16px);
}
.et-grid-no-spacing>.et-size-80, .et-grid-no-spacing>.et-size-md-80.et-size-md-80 {
    width: 80%}
.et-size-90, .et-size-md-90.et-size-md-90 {
    width: calc(90% - 16px);
}
.et-grid-no-spacing>.et-size-90, .et-grid-no-spacing>.et-size-md-90.et-size-md-90 {
    width: 90%}

.et-size-100, .et-size-md-100.et-size-md-100 {
    width: calc(100% - 16px);
}
.et-grid-no-spacing>.et-size-100, .et-grid-no-spacing>.et-size-md-100.et-size-md-100 {
    width: 100%}
.et-block--1-col, .et-block--1-col-md.et-block--1-col-md {
    width: calc(12.5% - 16px);
}
.et-grid-no-spacing>.et-block--1-col, .et-grid-no-spacing>.et-block--1-col-md.et-block--1-col-md {
    width: 12.5%}
.et-block--2-col, .et-block--2-col-md.et-block--2-col-md {
    width: calc(25% - 16px);
}
.et-grid-no-spacing>.et-block--2-col, .et-grid-no-spacing>.et-block--2-col-md.et-block--2-col-md {
    width: 25%}
.et-block--3-col, .et-block--3-col-md.et-block--3-col-md {
    width: calc(37.5% - 16px);
}
.et-grid-no-spacing>.et-block--3-col, .et-grid-no-spacing>.et-block--3-col-md.et-block--3-col-md {
    width: 37.5%}
.et-block--4-col, .et-block--4-col-md.et-block--4-col-md {
    width: calc(50% - 16px);
}
.et-grid-no-spacing>.et-block--4-col, .et-grid-no-spacing>.et-block--4-col-md.et-block--4-col-md {
    width: 50%}
.et-block--5-col, .et-block--5-col-md.et-block--5-col-md {
    width: calc(62.5% - 16px);
}
.et-grid-no-spacing>.et-block--5-col, .et-grid-no-spacing>.et-block--5-col-md.et-block--5-col-md {
    width: 62.5%}
.et-block--6-col, .et-block--6-col-md.et-block--6-col-md {
    width: calc(75% - 16px);
}
.et-grid-no-spacing>.et-block--6-col, .et-grid-no-spacing>.et-block--6-col-md.et-block--6-col-md {
    width: 75%}
.et-block--7-col, .et-block--7-col-md.et-block--7-col-md {
    width: calc(87.5% - 16px);
}
.et-grid-no-spacing>.et-block--7-col, .et-grid-no-spacing>.et-block--7-col-md.et-block--7-col-md {
    width: 87.5%}
.et-block--8-col, .et-block--8-col-md.et-block--8-col-md {
    width: calc(100% - 16px);
}
.et-grid-no-spacing>.et-block--8-col, .et-grid-no-spacing>.et-block--8-col-md.et-block--8-col-md {
    width: 100%}
.et-block--9-col, .et-block--9-col-md.et-block--9-col-md {
    width: calc(100% - 16px);
}
.et-grid-no-spacing>.et-block--9-col, .et-grid-no-spacing>.et-block--9-col-md.et-block--9-col-md {
    width: 100%}
.et-block--10-col, .et-block--10-col-md.et-block--10-col-md {
    width: calc(100% - 16px);
}
.et-grid-no-spacing>.et-block--10-col, .et-grid-no-spacing>.et-block--10-col-md.et-block--10-col-md {
    width: 100%}
.et-block--11-col, .et-block--11-col-md.et-block--11-col-md {
    width: calc(100% - 16px);
}
.et-grid-no-spacing>.et-block--11-col, .et-grid-no-spacing>.et-block--11-col-md.et-block--11-col-md {
    width: 100%}
.et-block--12-col, .et-block--12-col-md.et-block--12-col-md {
    width: calc(100% - 16px);
}
.et-grid-no-spacing>.et-block--12-col, .et-grid-no-spacing>.et-block--12-col-md.et-block--12-col-md {
    width: 100%}
.et-block--1-offset, .et-block--1-offset-md.et-block--1-offset-md {
    margin-left: calc(12.5% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--1-offset, .et-grid.et-grid-no-spacing>.et-block--1-offset-md.et-block--1-offset-md {
    margin-left: 12.5%}
.et-block--2-offset, .et-block--2-offset-md.et-block--2-offset-md {
    margin-left: calc(25% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--2-offset, .et-grid.et-grid-no-spacing>.et-block--2-offset-md.et-block--2-offset-md {
    margin-left: 25%}
.et-block--3-offset, .et-block--3-offset-md.et-block--3-offset-md {
    margin-left: calc(37.5% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--3-offset, .et-grid.et-grid-no-spacing>.et-block--3-offset-md.et-block--3-offset-md {
    margin-left: 37.5%}
.et-block--4-offset, .et-block--4-offset-md.et-block--4-offset-md {
    margin-left: calc(50% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--4-offset, .et-grid.et-grid-no-spacing>.et-block--4-offset-md.et-block--4-offset-md {
    margin-left: 50%}
.et-block--5-offset, .et-block--5-offset-md.et-block--5-offset-md {
    margin-left: calc(62.5% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--5-offset, .et-grid.et-grid-no-spacing>.et-block--5-offset-md.et-block--5-offset-md {
    margin-left: 62.5%}
.et-block--6-offset, .et-block--6-offset-md.et-block--6-offset-md {
    margin-left: calc(75% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--6-offset, .et-grid.et-grid-no-spacing>.et-block--6-offset-md.et-block--6-offset-md {
    margin-left: 75%}
.et-block--7-offset, .et-block--7-offset-md.et-block--7-offset-md {
    margin-left: calc(87.5% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--7-offset, .et-grid.et-grid-no-spacing>.et-block--7-offset-md.et-block--7-offset-md {
    margin-left: 87.5%}
}
@media (min-width: 840px) {
    .et-grid {
    padding: 8px;
}
.et-block {
    margin: 8px;
    width: calc(33.33333% - 16px);
}
.et-grid-no-spacing>.et-block {
    width: 33.33333%}
.et-hide-lg {
    display: none !important;
}
.et-size-10, .et-size-lg-10.et-size-lg-10 {
    width: calc(10% - 16px);
}
.et-grid-no-spacing>.et-size-10, .et-grid-no-spacing>.et-size-lg-10.et-size-lg-10 {
    width: 10%}
.et-size-20, .et-size-lg-20.et-size-lg-20 {
    width: calc(20% - 16px);
}
.et-grid-no-spacing>.et-size-20, .et-grid-no-spacing>.et-size-lg-20.et-size-lg-20 {
    width: 20%}
.et-size-25, .et-size-lg-25.et-size-lg-25 {
    width: calc(25% - 16px);
}
.et-grid-no-spacing>.et-size-25, .et-grid-no-spacing>.et-size-lg-25.et-size-lg-25 {
    width: 25%}

.et-size-30, .et-size-lg-30.et-size-lg-30 {
    width: calc(30% - 16px);
}
.et-grid-no-spacing>.et-size-30, .et-grid-no-spacing>.et-size-lg-30.et-size-lg-30 {
    width: 30%}

.et-size-40, .et-size-lg-40.et-size-lg-40 {
  width: calc(40% - 16px);
}
.et-grid-no-spacing>.et-size-40, .et-grid-no-spacing>.et-size-lg-40.et-size-lg-40 {
    width: 40%}


.et-size-60, .et-size-lg-60.et-size-lg-60 {
  width: calc(60% - 16px);
}
.et-grid-no-spacing>.et-size-60, .et-grid-no-spacing>.et-size-lg-60.et-size-lg-60 {
    width: 60%}


.et-size-50, .et-size-lg-50.et-size-lg-50 {
    width: calc(50% - 16px);
}
.et-grid-no-spacing>.et-size-50, .et-grid-no-spacing>.et-size-lg-50.et-size-lg-50 {
    width: 50%}

.et-size-70, .et-size-lg-70.et-size-lg-70 {
    width: calc(70% - 16px);
}
.et-grid-no-spacing>.et-size-70, .et-grid-no-spacing>.et-size-lg-70.et-size-lg-70 {
    width: 70%}
.et-size-75, .et-size-lg-75.et-size-lg-75 {
    width: calc(75% - 16px);
}
.et-grid-no-spacing>.et-size-75, .et-grid-no-spacing>.et-size-lg-75.et-size-lg-50 {
    width: 75%}
.et-size-80, .et-size-lg-80.et-size-lg-80 {
    width: calc(80% - 16px);
}
.et-grid-no-spacing>.et-size-80, .et-grid-no-spacing>.et-size-lg-80.et-size-lg-80 {
    width: 80%}
.et-size-90, .et-size-lg-90.et-size-lg-90 {
    width: calc(90% - 16px);
}
.et-grid-no-spacing>.et-size-90, .et-grid-no-spacing>.et-size-lg-90.et-size-lg-90 {
    width: 90%}

.et-size-100, .et-size-lg-100.et-size-lg-100 {
    width: calc(100% - 16px);
}
.et-grid-no-spacing>.et-size-100, .et-grid-no-spacing>.et-size-lg-100.et-size-lg-100 {
    width: 100%}
.et-block--1-col, .et-block--1-col-lg.et-block--1-col-lg {
    width: calc(8.33333% - 16px);
}
.et-grid-no-spacing>.et-block--1-col, .et-grid-no-spacing>.et-block--1-col-lg.et-block--1-col-lg {
    width: 8.33333%}
.et-block--2-col, .et-block--2-col-lg.et-block--2-col-lg {
    width: calc(16.66667% - 16px);
}
.et-grid-no-spacing>.et-block--2-col, .et-grid-no-spacing>.et-block--2-col-lg.et-block--2-col-lg {
    width: 16.66667%}
.et-block--3-col, .et-block--3-col-lg.et-block--3-col-lg {
    width: calc(25% - 16px);
}
.et-grid-no-spacing>.et-block--3-col, .et-grid-no-spacing>.et-block--3-col-lg.et-block--3-col-lg {
    width: 25%}
.et-block--4-col, .et-block--4-col-lg.et-block--4-col-lg {
    width: calc(33.33333% - 16px);
}
.et-grid-no-spacing>.et-block--4-col, .et-grid-no-spacing>.et-block--4-col-lg.et-block--4-col-lg {
    width: 33.33333%}
.et-block--5-col, .et-block--5-col-lg.et-block--5-col-lg {
    width: calc(41.66667% - 16px);
}
.et-grid-no-spacing>.et-block--5-col, .et-grid-no-spacing>.et-block--5-col-lg.et-block--5-col-lg {
    width: 41.66667%}
.et-block--6-col, .et-block--6-col-lg.et-block--6-col-lg {
    width: calc(50% - 16px);
}
.et-grid-no-spacing>.et-block--6-col, .et-grid-no-spacing>.et-block--6-col-lg.et-block--6-col-lg {
    width: 50%}
.et-block--7-col, .et-block--7-col-lg.et-block--7-col-lg {
    width: calc(58.33333% - 16px);
}
.et-grid-no-spacing>.et-block--7-col, .et-grid-no-spacing>.et-block--7-col-lg.et-block--7-col-lg {
    width: 58.33333%}
.et-block--8-col, .et-block--8-col-lg.et-block--8-col-lg {
    width: calc(66.66667% - 16px);
}
.et-grid-no-spacing>.et-block--8-col, .et-grid-no-spacing>.et-block--8-col-lg.et-block--8-col-lg {
    width: 66.66667%}
.et-block--9-col, .et-block--9-col-lg.et-block--9-col-lg {
    width: calc(75% - 16px);
}
.et-grid-no-spacing>.et-block--9-col, .et-grid-no-spacing>.et-block--9-col-lg.et-block--9-col-lg {
    width: 75%}
.et-block--10-col, .et-block--10-col-lg.et-block--10-col-lg {
    width: calc(83.33333% - 16px);
}
.et-grid-no-spacing>.et-block--10-col, .et-grid-no-spacing>.et-block--10-col-lg.et-block--10-col-lg {
    width: 83.33333%}
.et-block--11-col, .et-block--11-col-lg.et-block--11-col-lg {
    width: calc(91.66667% - 16px);
}
.et-grid-no-spacing>.et-block--11-col, .et-grid-no-spacing>.et-block--11-col-lg.et-block--11-col-lg {
    width: 91.66667%}
.et-block--12-col, .et-block--12-col-lg.et-block--12-col-lg {
    width: calc(100% - 16px);
}
.et-grid-no-spacing>.et-block--12-col, .et-grid-no-spacing>.et-block--12-col-lg.et-block--12-col-lg {
    width: 100%}
.et-block--1-offset, .et-block--1-offset-lg.et-block--1-offset-lg {
    margin-left: calc(8.33333% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--1-offset, .et-grid.et-grid-no-spacing>.et-block--1-offset-lg.et-block--1-offset-lg {
    margin-left: 8.33333%}
.et-block--2-offset, .et-block--2-offset-lg.et-block--2-offset-lg {
    margin-left: calc(16.66667% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--2-offset, .et-grid.et-grid-no-spacing>.et-block--2-offset-lg.et-block--2-offset-lg {
    margin-left: 16.66667%}
.et-block--3-offset, .et-block--3-offset-lg.et-block--3-offset-lg {
    margin-left: calc(25% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--3-offset, .et-grid.et-grid-no-spacing>.et-block--3-offset-lg.et-block--3-offset-lg {
    margin-left: 25%}
.et-block--4-offset, .et-block--4-offset-lg.et-block--4-offset-lg {
    margin-left: calc(33.33333% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--4-offset, .et-grid.et-grid-no-spacing>.et-block--4-offset-lg.et-block--4-offset-lg {
    margin-left: 33.33333%}
.et-block--5-offset, .et-block--5-offset-lg.et-block--5-offset-lg {
    margin-left: calc(41.66667% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--5-offset, .et-grid.et-grid-no-spacing>.et-block--5-offset-lg.et-block--5-offset-lg {
    margin-left: 41.66667%}
.et-block--6-offset, .et-block--6-offset-lg.et-block--6-offset-lg {
    margin-left: calc(50% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--6-offset, .et-grid.et-grid-no-spacing>.et-block--6-offset-lg.et-block--6-offset-lg {
    margin-left: 50%}
.et-block--7-offset, .et-block--7-offset-lg.et-block--7-offset-lg {
    margin-left: calc(58.33333% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--7-offset, .et-grid.et-grid-no-spacing>.et-block--7-offset-lg.et-block--7-offset-lg {
    margin-left: 58.33333%}
.et-block--8-offset, .et-block--8-offset-lg.et-block--8-offset-lg {
    margin-left: calc(66.66667% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--8-offset, .et-grid.et-grid-no-spacing>.et-block--8-offset-lg.et-block--8-offset-lg {
    margin-left: 66.66667%}
.et-block--9-offset, .et-block--9-offset-lg.et-block--9-offset-lg {
    margin-left: calc(75% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--9-offset, .et-grid.et-grid-no-spacing>.et-block--9-offset-lg.et-block--9-offset-lg {
    margin-left: 75%}
.et-block--10-offset, .et-block--10-offset-lg.et-block--10-offset-lg {
    margin-left: calc(83.33333% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--10-offset, .et-grid.et-grid-no-spacing>.et-block--10-offset-lg.et-block--10-offset-lg {
    margin-left: 83.33333%}
.et-block--11-offset, .et-block--11-offset-lg.et-block--11-offset-lg {
    margin-left: calc(91.66667% + 8px);
}
.et-grid.et-grid-no-spacing>.et-block--11-offset, .et-grid.et-grid-no-spacing>.et-block--11-offset-lg.et-block--11-offset-lg {
    margin-left: 91.66667%}
}

.intro-header{
display: flex;
  align-items: center; 
  min-height: 25vh;
  justify-content: center;
  width: 100%;
  height: 100%;
  margin: 0;
  margin: auto;

  background: color-primary}

  @element '.intro-header' \a\n\d (min-width: 960px) {
  .intro-header {
    background: bright-black;
    color: off-white;
  }
}


      
</style>
