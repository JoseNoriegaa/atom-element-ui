# [Vue](https://vuejs.org/) [Element-UI](https://element.eleme.io/) Snippets
_feel free to send a pull request if you want to contribute._

Description:
This is an extension of code snippets for the [Element-UI](https://element.eleme.io/) library in [Atom](https://atom.io/) text editor.


Note: it is necessary to have installed the extension "[language-vue](https://atom.io/packages/language-vue)" or something similar.


## Installation:
For install this extension, there are a few steps.
1. Open "[Atom](https://atom.io/)" and find the "Install Packages" section.
    ```
    Packages -> Settings View -> Install Packages/Themes
    ```
2. Find the [element-ui-snippets](https://atom.io/packages/element-ui-snippets) extension and install it

## Component list
- Basics
  - [`el-col`](#column)
  - [`el-row`](#row)
  - [`el-container`](#container)
  - [`el-button`](#button)
  - [`el-link`](#link)
- Form
  - [`el-radio`](#radio)
  - [`el-radio-group`](#radio)
  - [`el-checkbox`](#checkbox)
  - [`el-checkbox-group`](#checkbox)
  - [`el-checkbox-button`](#checkbox)
  - [`el-input`](#inputs)
  - [`el-input-number`](#inputs)
  - [`el-select`](#select)
  - [`el-option`](#select)
  - [`el-cascader`](#cascader)
  - [`el-switch`](#switch)
  - [`el-slider`](#slider)
  - [`el-time-picker`](#time-picker)
  - [`el-time-select`](#time-picker)
  - [`el-date-picker`](#date-time-picker)
  - [`el-upload`](#upload)
  - [`el-color-picker`](#color-picker)
  - [`el-transfer`](#transfer)
  - [`el-form`](#form)
  - [`el-form-item`](#form)
- Data
  - [`el-table`](#table)
  - [`el-table-column`](#table)
  - [`el-tag`](#tag)
  - [`el-tree`](#tree)
  - [`el-pagination`](#pagination)
  - [`el-badge`](#badge)
- Notice
  - [`el-alert`](#alert)
  - [Loading](#javascript)
  - [Message](#javascript)
  - [MessageBox](#javascript)
  - [Notification](#javascript)
- Navigation
  - [`el-menu`](#menu)
  - [`el-menu-item`](#menu)
  - [`el-submenu`](#menu)
  - [`el-tabs`](#tabs)
  - [`el-tab-pane`](#tabs)
  - [`el-breadcrumb`](#breadcrumb)
  - [`el-breadcrumb-item`](#breadcrumb)
  - [`el-page-header`](#page-header)
  - [`el-dropdown`](#dropdown)
  - [`el-dropdown-menu`](#dropdown)
  - [`el-steps`](#steps)
  - [`el-step`](#steps)
- Others
  - [`el-dialog`](#dialog)
  - [`el-tooltip`](#tooltip)
  - [`el-popover`](#popover)
  - [`el-popconfirm`](#popconfirm)
  - [`el-card`](#card)
  - [`el-carousel`](#carousel)
  - [`el-collapse`](#collapse)
  - [`el-collapse-item`](#collapse)
  - [`el-timeline`](#timeline)
  - [`el-timeline-item`](#timeline)
  - [`el-divider`](#divider)
  - [`el-calendar`](#calendar)
  - [`el-image`](#image)
  - [`el-backtop`](#backtop)
  - [Infinite Scroll](#infinite-scroll)
  - [`el-avatar`](#avatar)
  - [`el-drawer`](#drawer)

## Snippets:

### Basic

##### [Column](https://element.eleme.io/#/en-US/component/layout#col-attributes)
- elcol
  ```html
  <el-col>

  </el-col>
  ```
- elcolr
  ```html
  <el-col
    :xs=""
    :sm=""
    :md=""
    :lg=""
    :xl=""
  >

  </el-col>
  ```
- elcolsp
  ```html
  <el-col :span="">

  </el-col>
  ```
- elcolfull
  ```html
  <el-col
    :span=""
    :offset=""
    :push=""
    :pull=""
    :xs=""
    :sm=""
    :md=""
    :lg=""
    :xl=""
    tag=""
  >

  </el-col>
  ```
##### [Row](https://element.eleme.io/#/en-US/component/layout#row-attributes)
- elrow
  ```html
  <el-row>

  </el-row>
  ```
- elrowflex
  ```html
  <el-row
    type="flex"
    align=""
    justify=""
  >

  </el-row>
  ```
- elrowc2
  ```html
  <el-row>
    <el-col :span="12">

    </el-col>
    <el-col :span="12">

    </el-col>
  </el-row>
  ```
- elrowg
  ```html
  <el-row :gutter="">

  </el-row>
  ```
- elrowfull
  ```html
  <el-row
    :gutter="0"
    type=""
    tag="div"
    justify="start"
    align="top"
  >

  </el-row>
  ```
##### [Container](https://element.eleme.io/#/en-US/component/container)
- elcontainer
  ```html
  <el-container>
    <el-aside width="200px">
      <!-- Aside content -->

    </el-aside>
    <el-container>
      <el-header height="">
        <!-- Header content -->

      </el-header>
      <el-main height="">
        <!-- Main content -->

      </el-main>
    </el-container>
  </el-container>
  ```
##### [Button](https://element.eleme.io/#/en-US/component/button)
- elbtn
  ```html
  <el-button
    type="text"
    @click.native=""
  >

  </el-button>
  ```
- elbtnfull
  ```html
  <el-button
    size="medium"
    type="primary"
    :plain="false"
    :round="false"
    :circle="false"
    :loading="false"
    :disabled="false"
    icon=""
    :autofocus="false"
    native-type="button"
    @click.native=""
  >

  </el-button>
  ```
##### [Link](https://element.eleme.io/#/en-US/component/link)
  - ellink
  ```html
  <el-link
    href="url"
    target="_self"
  >

  </el-link>
  ```
  - ellinkfull
  ```html
  <el-link
    type="primary"
    underline="true"
    disabled="false"
    href="url"
    target="_self"
    icon=""
  >
    
  </el-link>
  ```
### Form

##### [Radio](https://element.eleme.io/#/en-US/component/radio)
- elradio
  ```html
  <el-radio
    v-model=""
    label=""
  >

  </el-radio>
  ```
- elradio2
  ```html
  <el-radio
    v-model=""
    label=""
  >
     option A
  </el-radio>

  <el-radio
    v-model=""
    label=""
  >
     option B
  </el-radio>
  ```
- elradiofull
  ```html
  <el-radio
    v-model=""
    label=""
    :disabled="false"
    :border="false"
    size="medium"
    name=""
    @change=""
  >
    
  </el-radio>
  ```
- elradiogroup
  ```html
  <el-radio-group
    v-model=""
    @change=""
  >
    
  </el-radio-group>
  ```
- elradiogroupfull
  ```html
  <el-radio-group
    v-model=""
    size="medium"
    :disabled="false"
    text-color="#FFFFFF"
    fill="#409EFF"
    @change=""
  >
    
  </el-radio-group>
  ````
##### [Checkbox](https://element.eleme.io/#/en-US/component/checkbox)
- elcheck
  ```html
  <el-checkbox v-model="">

  </el-checkbox>
  ```
- elcheckgr
  ```html
  <el-checkbox-group
    v-model=""
    size="small"
  >

  </el-checkbox-group>
  ```
- elcheckfull
  ```html
  <el-checkbox
    v-model=""
    label=""
    true-label=""
    false-label=""
    :disabled="false"
    :border="false"
    size="medium"
    name=""
    :checked="false"
    :indeterminate="false"
    @change=""
  >
    
  </el-checkbox>
  ```
- elcheckgrfull
  ```html
  <el-checkbox-group
    v-model=""
    size="medium"
    :disabled="false"
    :min=""
    :max=""
    text-color="#FFFFFF"
    fill="#409EFF"
    @change=""
  >
    
  </el-checkbox-group>
  ```
- elcheckbtn
  ```html
  <el-checkbox-button
    :label=""
    true-label=""
    false-label=""
  >
    
  </el-checkbox-button>
  ```
- elcheckbtnfull
  ```html
  <el-checkbox-button
    label=""
    true-label=""
    false-label=""
    :disabled="false"
    name=""
    :checked="false"
  >
    
  </el-checkbox-button>
  ```
##### [Inputs](https://element.eleme.io/#/en-US/component/input)
- elinput
  ```html
  <el-input
    v-model=""
    placeholder=""
  />
  ```
- elinputpicon
  ```html
  <el-input
    v-model=""
    placeholder=""
    prefix-icon=""
  />
  ```
- elinputsicon
  ```html
  <el-input
    v-model=""
    placeholder=""
    suffix-icon=""
  />
  ```
- eltextarea
  ```html
  <el-input
    type="textarea"
    :rows=""
    placeholder=""
    v-model=""
  />
  ```
- eltextareaauto
  ```html
  <el-input
    type="textarea"
    :rows=""
    placeholder=""
    v-model=""
    autosize
  />
  ```
- eltextareanr
  ```html
  <el-input
    type="textarea"
    :rows=""
    placeholder=""
    v-model=""
    resize="none"
  />
  ```
- elinputnum
  ```html
  <el-input-number
    v-model=""
    size="small"
    :precision=""
    :step=""
    :max=""
    :controls=" true"
  />
  ```
##### [Select](https://element.eleme.io/#/en-US/component/select)
- elselect
  ```html
  <el-select
    v-model=""
    placeholder=""
  >
    <el-option
      v-for="item in Array"
      :key="item.value"
      :label="item.label"
      :value="item.value"
      :disabled="item.disabled"
    />
  </el-select>
  ```
- elopt
  ```html
  <el-option
    label=""
    value=""
    :disabled="false"
  />
  </el-option>
  ```
##### [Cascader](https://element.eleme.io/#/en-US/component/cascader)
- elcascader
  ```html
  <el-cascader
    :options=""
    v-model=""
    @change=""
    placeholder=""
    expand-trigger="click"
  />
  ```
##### [Switch](https://element.eleme.io/#/en-US/component/switch)
- elswitch
  ```html
  <el-switch
    v-model=""
    active-value=""
    inactive-value=""
    active-text=""
    inactive-text=""
  />
  ```
##### [Slider](https://element.eleme.io/#/en-US/component/slider)
- elslider
  ```html
  <el-slider
    v-model=""
    vertical="false"
  />
  ```
##### [Time picker](https://element.eleme.io/#/en-US/component/time-picker)
- eltimepicker
  ```html
  <el-time-picker
    v-model=""
    :picker-options="{
      selectableRange: '18:30:00 - 20:30:00',
    }"
    placeholder="Arbitrary time"
  />
  ```
- eltimeselect
  ```html
  <el-time-select
    v-model=""
    :picker-options="{
      start: '08:30',
      step: '00:15',
      end: '18:30',
    }"
    placeholder="Select time"
  />
  ```
##### [Date time picker](https://element.eleme.io/#/en-US/component/date-picker)
- eldatepicker
  ```html
  <el-date-picker
    v-model=""
    type="date"
    placeholder=""
  />
  ```
##### [Upload](https://element.eleme.io/#/en-US/component/upload)
- elupload
  ```html
  <el-upload
    action=""
    :on-preview=""
    :on-remove=""
    :multiple="true"
    :limit=""
    :on-exceed=""
    :file-list=""
  >
    <el-button
      size="small"
      type="primary"
    >
      upload file
    </el-button>
    <div
      slot="tip"
      class="el-upload__tip"
    >
      Only jpg/png files with a size smaller than 500kb
    </div>
  </el-upload>
  ```
- eluploadavatar
  ```html
  <el-upload
    action=""
    list-type="picture-card"
    :on-preview="handlePictureCardPreview"
    :on-remove="handleRemove"
  >
    <i class="el-icon-plus"></i>
  </el-upload>
  <el-dialog :visible.sync="dialogVisible">
    <img width="100%" :src="dialogImageUrl" alt="">
  </el-dialog>
  ```
##### [Rate](https://element.eleme.io/#/en-US/component/rate)
- elrate
  ```html
  <el-rate v-model=""/>
  ```
##### [Color picker](https://element.eleme.io/#/en-US/component/color-picker)
- elcolorpicker
  ```html
  <el-color-picker v-model=""/>
  ```
##### [Transfer](https://element.eleme.io/#/en-US/component/transfer)
- eltrans
  ```html
  <el-transfer
    v-model=""
    :titles="['List 1', 'List 2']"
    :data=""
  />
  ```
##### [Form](https://element.eleme.io/#/en-US/component/form)
- elform
  ```html
  <el-form
    :model=""
    :rules=""
    ref=""
    @submit.native.prevent
    @keyup.enter.native=""
  >
    <!-- FORM ITEMS -->

    <!-- Button Submit -->
    <el-form-item>
      <el-button
        type="primary"
        @click=""
        :loading="false"
      >

      </el-button>
    </el-form-item>
  </el-form>
  ```
- elformitm
  ```html
  <el-form-item prop="">

  </el-form-item>
  ```

### Data

##### [Table](https://element.eleme.io/#/en-US/component/table)
- eltable
  ```html
  <el-table :data="tableData">

  </el-table>
  ```
- eltablecol
  ```html
  <el-table-column
    prop=""
    label=""
    width=""
  />
  ```
##### [Tag](https://element.eleme.io/#/en-US/component/tag)
- eltag
  ```html
  <el-tag
    @click="closeHandler()"
    type=""
    :closable="false"
  >
    tag text
  </el-tag>
  ```
##### [Progress](https://element.eleme.io/#/en-US/component/progress)
- elprogress
  ```html
  <el-progress
   type="line"
   :percentage=""
   :status=""
  />
  ```
##### [Tree](https://element.eleme.io/#/en-US/component/tree)
- eltree
  ```html
  <el-tree
    :data=""
    :props=""
    @node-click=""
  />
  ```
##### [Pagination](https://element.eleme.io/#/en-US/component/pagination)
- elpagination
  ```html
  <el-pagination
    @size-change="sizeChange"
    @current-change="currentChange"
    :current-page="currentPage"
    :page-sizes="[20, 40, 80, 100]"
    :page-size="pageSize"
    layout="total, sizes, prev, pager, next, jumper"
    :total="totalNum" background>
  </el-pagination>
  ```
##### [Badge](https://element.eleme.io/#/en-US/component/badge)
- elbadge
  ```html
  <el-badge
    :value=""
    size="small"
  >

  </el-badge>
  ```

### Notice

##### [Alert](https://element.eleme.io/#/en-US/component/alert)
- elalrt
  ```html
  <el-alert
    title="Alert title"
    type="success"
    :closable="false"
    :show-icon="true"
  />
  ```

### Navigation

##### [Menu](https://element.eleme.io/#/en-US/component/menu)
- elmenu
  ```html
  <el-menu
    :default-active=""
    mode="horizontal"
    @select="handleSelect"
  >

  </el-menu>
  ```
- elmenuitm
  ```html
  <el-menu-item index="">
    Navigation option
  </el-menu-item>
  ```
- elsubmenu
  ```html
  <el-submenu index="">
    <template slot="title">
      title
    </template>
    <el-menu-item index="-1">
      item one
    </el-menu-item>
  </el-submenu>
  ```
- elmenuv
  ```html
  <el-menu
    mode="vertical"
    :default-active=""
    :collapse="false"
    background-color="#304156"
    text-color="#bfcbd9"
    active-text-color="#409EFF"
  >

  </el-menu>
  ```
##### [Tabs](https://element.eleme.io/#/en-US/component/tabs)
- eltabs
  ```html
  <el-tabs
    v-model=""
    type="card"
  >

  </el-tabs>
  ```
- eltabp
  ```html
  <el-tab-pane
    :label=""
    :name=""
  >

  </el-tab-pane>
  ```
##### [Breadcrumb](https://element.eleme.io/#/en-US/component/breadcrumb)
- elbreadcrumb
  ```html
  <el-breadcrumb separator="/">
    <el-breadcrumb-item
      :to="{ path: '/' }"
    >

    </el-breadcrumb-item>
  </el-breadcrumb>
  ```
- elbreadcrumbitm
  ```html
  <el-breadcrumb-item>

  </el-breadcrumb-item>
  ```
##### [Page Header](https://element.eleme.io/#/en-US/component/page-header)
- elpageheader
  ```html
  <el-page-header @back="" content="">
    
  </el-page-header>
  ```
- elpageheaderfull
  ```html
  <el-page-header
    title="Back"
    content=""
    @back=""
  >
    
  </el-page-header>
  ```
##### [Dropdown](https://element.eleme.io/#/en-US/component/dropdown)
- eldropdown
  ```html
  <el-dropdown>
    <span style="cursor: pointer; color: #409eff;">
      Dropdown List
      <i class="el-icon-arrow-down el-icon--right"/>
    </span>
    <el-dropdown-menu slot="dropdown">
      <el-dropdown-item>Action 1</el-dropdown-item>
    </el-dropdown-menu>
  </el-dropdown>
  ```
- eldropdownmenu
  ```html
  <el-dropdown-menu slot="dropdown">

  </el-dropdown-menu>
  ```
- eldropdownitm
  ```html
  <el-dropdown-item>

  </el-dropdown-item>
  ```
##### [Steps](https://element.eleme.io/#/en-US/component/steps)
- elsteps
  ```html
  <el-steps :active="step" finish-status="success">
    <el-step title="step 1"/>
  </el-steps>
  ```
- elstep
  ```html
  <el-step title=""/>
  ```

### Others

##### [Dialog](https://element.eleme.io/#/en-US/component/dialog)
- eldialog
  ```html
  <el-dialog
    title="Tips"
    :visible.sync="dialogVisible"
    width="30%"
    :before-close="handleClose"
  >

    <span slot="footer" class="dialog-footer">
      <el-button @click="dialogVisible = false">
        Cancel
      </el-button>
      <el-button
        type="primary"
        @click="dialogVisible = false"
      >
        Confirm
      </el-button>
    </span>
  </el-dialog>
  ```
##### [Tooltip](https://element.eleme.io/#/en-US/component/tooltip)
- eltooltip
  ```html
  <el-tooltip
    effect="light"
    content=""
    placement="top-start"
  >

  </el-tooltip>
  ```
##### [Popover](https://element.eleme.io/#/en-US/component/popover)
- elpopover
  ```html
  <el-popover
    placement="top-start"
    title="Title"
    width="200"
    trigger="hover"
    content="this is content, this is content, this is content"
  >
    <el-button slot="reference">
      Hover to activate
    </el-button>
  </el-popover>
  ```
##### [Popconfirm](https://element.eleme.io/#/en-US/component/popconfirm)
- elpopconfirm
  ```html
  <el-popconfirm
    title="Are you sure to delete this?"
  >
    <el-button slot="reference">
      Delete
    </el-button>
  </el-popconfirm>
  ```
- elpopconfirmfull
  ```html
  <el-popconfirm
    title="Are you sure to delete this?"
    confirmButtonText="YES"
    cancelButtonText="NO"
    confirmButtonType="primary"
    cancelButtonType="text"
    icon="el-icon-question"
    iconColor="#FF9900"
    :hideIcon="false"
  >
    <el-button slot="reference">
      Delete
    </el-button>
  </el-popconfirm>
  ````

##### [Card](https://element.eleme.io/#/en-US/component/card)
- elcard
  ```html
  <el-card class="">
    <div slot="header" class="clearfix">
      <span>Card name</span>
    </div>

  </el-card>
  ```
##### [Carousel](https://element.eleme.io/#/en-US/component/carousel)
- elcarousel
  ```html
  <el-carousel height="150px">

  </el-carousel>
  ```
- elcarouselitm
  ```html
  <el-carousel-item>

  </el-carousel-item>
  ```
##### [Collapse](https://element.eleme.io/#/en-US/component/collapse)
- elcollapse
  ```html
  <el-collapse
    v-model=""
    @change="handleChange"
  >

  </el-collapse>
  ```
- elcollapseitm
  ```html
  <el-collapse-item
    title=""
    name=""
  >

  </el-collapse-item>
  ```
##### [Timeline](https://element.eleme.io/#/en-US/component/timeline)
- eltimeline
  ```html
  <el-timeline :reverse="false">
    
  </el-timeline>
  ```
- eltimelinefull
  ```html
  <el-timeline-item
    timestamp="YYYY-MM-DD"
    :hide-timestamp="false"
    placement="bottom"
    type="primary"
    color=""
    size="normal"
    icon=""
  >
    
  </el-timeline-item>
  ```
- eltimelineitem
  ```html
  <el-timeline-item
    timestamp="YYYY-MM-DD"
  >
    
  </el-timeline-item>
  ```
##### [Divider](https://element.eleme.io/#/en-US/component/divider)
- eldivider
  ```html
  <el-divider></el-divider>
  ```
- eldividerfull
  ```html
  <el-divider
    direction="horizontal"
    content-position="center"
  >
    
  </el-divider>
  ```
##### [Calendar](https://element.eleme.io/#/en-US/component/calendar)
- elcalendar
  ```html
  <el-calendar v-model="" />
  ```
- elcalendarfull
  ```html
  v-model=""
    :range="[]"
    :first-day-of-week="1"
  />
  ```
##### [Image](https://element.eleme.io/#/en-US/component/image)
- elimage
  ```html
  <el-image
    src=""
    fit="contain"
  >
    
  </el-image>
  ````
- elimagefull
  ```html
  <el-image
    src=""
    fit="contain"
    alt="image"
    referrer-policy=""
    :lazy="false"
    scroll-container=""
    :preview-src-list="[]"
    :z-index="2000"
    @load=""
    @error=""
  >
    
  </el-image>
  ```
##### [Backtop](https://element.eleme.io/#/en-US/component/backtop)
- elbacktop
  ```html
  <el-backtop target="">
    
  </el-backtop>
  ```
- elbacktopfull
  ```html
  <el-backtop
    target=""
    :visibility-height="200"
    :right="40"
    :bottom="40"
    @click=""
  >
    
  </el-backtop>
  ```
##### [Infinite Scroll](https://element.eleme.io/#/en-US/component/infinite-scroll)
- elinfinite
  ```html
  <ul
    class="infinite-list"
    v-infinite-scroll=""
    style="overflow:auto"
  >
    <li v-for="item in " class="infinite-list-item">
      
    </li>
  </ul>
  ```
##### [Avatar](https://element.eleme.io/#/en-US/component/avatar)
- elavatar
  ```html
  <el-avatar
    shape="circle"
    size="medium"
    src=""
  >
    
  </el-avatar>
  ```
- elavatarfull
  ```html
  <el-avatar
    icon=""
    size="medium"
    shape="circle"
    src=""
    srcSet=""
    alt=""
    fit="cover"
    @error="() => {}"
  >
    
  </el-avatar>
  ```
##### [Drawer](https://element.eleme.io/#/en-US/component/drawer)
- eldrawer
  ```html
  <el-drawer
    title=""
    :visible="false"
    direction="rtl"
  >
    
  </el-drawer>
  ```
- eldrawerfull
  ```html
  <el-drawer
    :append-to-body="false"
    :before-close=""
    :close-on-press-escape=""
    custom-class=""
    :destroy-on-close="false"
    :modal="true"
    :modal-append-to-body="true"
    direction="rtl"
    :show-close="true"
    size="30%"
    title=""
    :visible="false"
    :wrapperClosable="true"
    :withHeader="true"
    @open="() => {}"
    @opened="() => {}"
    @close="() => {}"
    @closed="() => {}"
  >
    
  </el-drawer>
  ```
### JavaScript
- [elnoti](https://element.eleme.io/#/en-US/component/notification)
  ```js
  this.$notify({
    title: 'Title',
    message: 'Message',
    type: 'success',
    duration: 2500,
  });
  ```
- [elmessage](https://element.eleme.io/#/en-US/component/message)
  ```js
  this.$message({
    type: '',
    message: '',
    showClose: false,
  });
  ```
- [elloading](https://element.eleme.io/#/en-US/component/loading)
  ```js
  this.$loading({
    lock: true,
    text: 'loading...',
    spinner: 'el-icon-loading',
    background: 'rgba(0, 0, 0, 0.7)',
  });
  ```
- [elalert](https://element.eleme.io/#/en-US/component/message-box)
  ```js
  this.$alert('This is a message', 'Title', {
    confirmButtonText: 'OK',
    callback: (action) => {},
  });
  ```
- [elconfirm](https://element.eleme.io/#/en-US/component/message-box)
  ```js
  this.$confirm('Message', 'Title', {
    confirmButtonText: 'OK',
    cancelButtonText: 'Cancel',
    type: 'warning',
  }).then(() => {

  }).catch(() => {

  });
  ```
- [elmsgbox](https://element.eleme.io/#/en-US/component/message-box)
  ```js
  this.$msgbox({
    title: 'Title',
    message: 'Title',
    showCancelButton: true,
    confirmButtonText: 'OK',
    cancelButtonText: 'Cancel',
    beforeClose: (action, instance, done) => {
      if (action === 'confirm') {
        instance.confirmButtonLoading = true;
        instance.confirmButtonText = 'Loading...';
        setTimeout(() => {
          done();
          setTimeout(() => {
            instance.confirmButtonLoading = false;
          }, 300);
        }, 3000);
      } else {
        done();
      }
    }
  }).then((action) => {
    // Do something
  });
  ```
- [elprompt](https://element.eleme.io/#/en-US/component/message-box)
  ```js
  this.$prompt('Please input your e-mail', 'Tip', {
    confirmButtonText: 'OK',
    cancelButtonText: 'Cancel',
    inputPattern: /[w!#$%&'*+/=?^_`{|~-]+(?:.[w!#$%&'*+/=?^_`{|}~-]+)*@(?:[w](?:[w-]*[w])?.)+[w](?:[w-]*[w])?/},
    inputErrorMessage: 'Invalid Email'
  }).then(data) => {
    // Do something
  }).catch(() => {
    // Do something
  });
  ```
# [License](https://github.com/JoseNoriegaa/atom-element-ui/blob/master/LICENSE)

