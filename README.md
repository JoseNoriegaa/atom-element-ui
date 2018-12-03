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

## Snippets:

### Basic

##### Column
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
- elcolflex
  ```html
  <el-col
    type="flex"
    align=""
    justify=""
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
    :xl=""
    :sm=""
    :md=""
    :lg=""
    :xl=""
    tag=""
  >

  </el-col>
  ```
##### Row
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
##### Container
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
##### Button
- elbtn
  ```html
  <el-button
    type="text"
    @click.native=""
  >

  </el-button>
  ```

### Form

##### Radio
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
    size="medium"
    :disabled="false"
  >

  </el-radio-group>
  ```
##### Checkbox
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
    :disabled="false"
    true-label=""
    false-label=""
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
    size="small"
    :disabled="false"
    :min=""
    :max=""
    text-color="#ffffff"
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
##### Inputs
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
##### Select
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
##### Cascader
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
##### Switch
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
##### Slider
- elslider
  ```html
  <el-slider
    v-model=""
    vertical="false"
  />
  ```
##### Time picker
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
##### Date time picker
- eldatepicker
  ```html
  <el-date-picker
    v-model=""
    type="date"
    placeholder=""
  />
  ```
##### Upload
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
##### Rate
- elrate
  ```html
  <el-rate v-model=""/>
  ```
##### Color picker
- elcolorpicker
  ```html
  <el-color-picker v-model=""/>
  ```
##### Transfer
- eltrans
  ```html
  <el-transfer
    v-model=""
    :titles="['List 1', 'List 2']"
    :data=""
  />
  ```
##### Form
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

##### Table
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
##### Tag
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
##### Progress
- elprogress
  ```html
  <el-progress
   type="line"
   :percentage=""
   :status=""
  />
  ```
##### Tree
- eltree
  ```html
  <el-tree
    :data=""
    :props=""
    @node-click=""
  />
  ```
##### Pagination
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
##### Badge
- elbadge
  ```html
  <el-badge
    :value=""
    size="small"
  >

  </el-badge>
  ```

### Notice

##### Alert
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

##### Menu
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
##### Tabs
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
##### Breadcrumb
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
##### Dropdown
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
##### Steps
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

##### Dialog
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
##### Tooltip
- eltooltip
  ```html
  <el-tooltip
    effect="light"
    content=""
    placement="top-start"
  >

  </el-tooltip>
  ```
##### Popover
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
##### Card
- elcard
  ```html
  <el-card class="">
    <div slot="header" class="clearfix">
      <span>Card name</span>
    </div>

  </el-card>
  ```
##### Carousel
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
##### Collapse
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

### JavaScript
- elnoti
  ```js
  this.$notify({
    title: 'Title',
    message: 'Message',
    type: 'success',
    duration: 2500,
  });
  ```
- elmessage
  ```js
  this.$message({
    type: '',
    message: '',
    showClose: false,
  });
  ```
- elloading
  ```js
  this.$loading({
    lock: true,
    text: 'loading...',
    spinner: 'el-icon-loading',
    background: 'rgba(0, 0, 0, 0.7)',
  });
  ```
- elalert
  ```js
  this.$alert('This is a message', 'Title', {
    confirmButtonText: 'OK',
    callback: (action) => {},
  });
  ```
- elconfirm
  ```js
  this.$confirm('Message', 'Title', {
    confirmButtonText: 'OK',
    cancelButtonText: 'Cancel',
    type: 'warning',
  }).then(() => {

  }).catch(() => {

  });
  ```
- elmsgbox
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
- elprompt
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

