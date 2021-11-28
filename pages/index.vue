<template>
  <div>
    <h2 class="block-title">Pagination</h2>
    <div class="block">
      <Pagination />
      <Pagination paginationClass="pagination-white" />
      <Pagination hasNotList />
      <Pagination hasNotList paginationClass="pagination-white" />
    </div>
    <h2 class="block-title">Horizontal nav</h2>
    <div class="block">
      <HorizontalNav :items="horizontalNav" />
    </div>
    <h2 class="block-title">Breadcrumb</h2>
    <div class="block">
      <Breadcrumb :items="breadcrumb" />
      <Breadcrumb :items="breadcrumb1" />
      <Breadcrumb :items="breadcrumb2" />
      <Breadcrumb :items="breadcrumb3" />
    </div>
    <h2 class="block-title">Button Group</h2>
    <div class="block">
      <BtnGroup :btn-list="btnList" btn-list-name="btnList" />
      <BtnGroup :btn-list="btnList1" btn-list-name="btnList1" />
      <BtnGroup :btn-list="btnList2" btn-list-name="btnList2" />
      <BtnGroup :btn-list="btnList3" btn-list-name="btnList3" />
    </div>
    <h2 class="block-title">Primary</h2>
    <div class="block">
      <div class="mb-30">
        <div class="d-flex">
          <Btn btnClass="btn-primary btn-small">Buttons</Btn>
          <Btn btnClass="btn-primary btn-small" icon-prev-text="IconPlus"
            >Button</Btn
          >
          <Btn btnClass="btn-primary btn-small" icon-next-text="IconNext"
            >Button</Btn
          >
          <Btn
            btnClass=" btn-primary btn-small"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
        <div class="d-flex">
          <Btn>Button</Btn>
          <Btn icon-prev-text="IconPlus">Button</Btn>
          <Btn icon-next-text="IconNext">Button</Btn>
          <Btn icon-prev-text="IconPlus" icon-next-text="IconNext">
            Button
          </Btn>
        </div>
        <div class="d-flex">
          <Btn btnClass="btn-primary btn-large">Large Button</Btn>
          <Btn btnClass="btn-primary btn-large" icon-prev-text="IconPlus"
            >Button</Btn
          >
          <Btn btnClass="btn-primary btn-large" icon-next-text="IconNext"
            >Button</Btn
          >
          <Btn
            btnClass="btn-primary btn-large"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
      </div>
      <div class="mb-30 bg-variant2">
        <div class="d-flex">
          <Btn btnClass="btn-white btn-small">Buttons</Btn>
          <Btn btnClass="btn-white btn-small" icon-prev-text="IconPlus"
            >Button</Btn
          >
          <Btn btnClass="btn-white btn-small" icon-next-text="IconNext"
            >Button</Btn
          >
          <Btn
            btnClass=" btn-white btn-small"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
        <div class="d-flex">
          <Btn btnClass="btn-white">Button</Btn>
          <Btn btnClass="btn-white" icon-prev-text="IconPlus">Button</Btn>
          <Btn btnClass="btn-white" icon-next-text="IconNext">Button</Btn>
          <Btn
            btnClass="btn-white"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
        <div class="d-flex">
          <Btn btnClass="btn-white btn-large">Large Button</Btn>
          <Btn btnClass="btn-white btn-large" icon-prev-text="IconPlus"
            >Button</Btn
          >
          <Btn btnClass="btn-white btn-large" icon-next-text="IconNext"
            >Button</Btn
          >
          <Btn
            btnClass="btn-white btn-large"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
      </div>
      <div class="mb-30">
        <div class="d-flex">
          <Btn btnClass="btn-outline-primary btn-small">Buttons</Btn>
          <Btn
            btnClass="btn-outline-primary btn-small"
            icon-prev-text="IconPlus"
            >Button</Btn
          >
          <Btn
            btnClass="btn-outline-primary btn-small"
            icon-next-text="IconNext"
            >Button</Btn
          >
          <Btn
            btnClass="btn-outline-primary btn-small"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
        <div class="d-flex">
          <Btn btnClass="btn-outline-primary">Button</Btn>
          <Btn btnClass="btn-outline-primary" icon-prev-text="IconPlus"
            >Button</Btn
          >
          <Btn btnClass="btn-outline-primary" icon-next-text="IconNext"
            >Button</Btn
          >
          <Btn
            btnClass="btn-outline-primary"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
        <div class="d-flex">
          <Btn btnClass="btn-outline-primary btn-large">Large Button</Btn>
          <Btn
            btnClass="btn-outline-primary btn-large"
            icon-prev-text="IconPlus"
            >Button</Btn
          >
          <Btn
            btnClass="btn-outline-primary btn-large"
            icon-next-text="IconNext"
            >Button</Btn
          >
          <Btn
            btnClass="btn-outline-primary btn-large"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
      </div>
      <div class="bg-variant2">
        <div class="d-flex">
          <Btn btnClass="btn-outline-white btn-small">Buttons</Btn>
          <Btn btnClass="btn-outline-white btn-small" icon-prev-text="IconPlus">
            Button
          </Btn>
          <Btn btnClass="btn-outline-white btn-small" icon-next-text="IconNext">
            Button
          </Btn>
          <Btn
            btnClass="btn-outline-white btn-small"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
        <div class="d-flex">
          <Btn btnClass="btn-outline-white">Button</Btn>
          <Btn btnClass="btn-outline-white" icon-prev-text="IconPlus">
            Button
          </Btn>
          <Btn btnClass="btn-outline-white" icon-next-text="IconNext">
            Button
          </Btn>
          <Btn
            btnClass="btn-outline-white"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
        <div class="d-flex">
          <Btn btnClass="btn-outline-white btn-large">Large Button</Btn>
          <Btn btnClass="btn-outline-white btn-large" icon-prev-text="IconPlus"
            >Button</Btn
          >
          <Btn btnClass="btn-outline-white btn-large" icon-next-text="IconNext"
            >Button</Btn
          >
          <Btn
            btnClass="btn-outline-white btn-large"
            icon-prev-text="IconPlus"
            icon-next-text="IconNext"
          >
            Button
          </Btn>
        </div>
      </div>
    </div>
    <h2 class="block-title">Button Icon</h2>
    <div class="block">
      <div class="d-flex align-items-center">
        <Btn
          btnClass="btn-social btn-social-large btn-primary"
          icon-prev-text="IconFb"
        ></Btn>
        <Btn btnClass="btn-social btn-primary" icon-prev-text="IconFb"></Btn>
        <Btn
          btnClass="btn-social btn-social-small btn-primary"
          icon-prev-text="IconFb"
        ></Btn>
      </div>
      <div class="d-flex align-items-center">
        <Btn
          btnClass="btn-social btn-social-large btn-outline-primary"
          icon-prev-text="IconFb"
        ></Btn>
        <Btn
          btnClass="btn-social btn-outline-primary"
          icon-prev-text="IconFb"
        ></Btn>
        <Btn
          btnClass="btn-social btn-social-small btn-outline-primary"
          icon-prev-text="IconFb"
        ></Btn>
      </div>
      <div class="d-flex align-items-center">
        <Btn
          btnClass="btn-social btn-social-large btn-white"
          icon-prev-text="IconFb"
        ></Btn>
        <Btn btnClass="btn-social btn-white" icon-prev-text="IconFb"></Btn>
        <Btn
          btnClass="btn-social btn-social-small btn-white"
          icon-prev-text="IconFb"
        ></Btn>
      </div>
    </div>
    <h2 class="block-title">Play button</h2>
    <div class="block">
      <div class="d-flex align-items-center">
        <Btn btnClass="btn-player btn-white" icon-prev-text="IconPlayer"></Btn>
        <Btn
          btnClass="btn-player btn-outline-primary"
          icon-prev-text="IconPlayer"
        ></Btn>
        <Btn
          btnClass="btn-player btn-primary"
          icon-prev-text="IconPlayer"
        ></Btn>
      </div>
    </div>
    <h2 class="block-title">Badge</h2>
    <div class="block">
      <div class="d-flex align-items-center">
        <Btn btnClass="btn-badge btn-small btn-primary">Badge</Btn>
        <Btn btnClass="btn-badge btn-small btn-light">Badge</Btn>
        <Btn btnClass="btn-badge btn-small btn-outline-primary">Badge</Btn>
        <Btn btnClass="btn-badge btn-small btn-white">Badge</Btn>
      </div>
    </div>
    <h2 class="block-title">Badge</h2>
    <div class="block">
      <div class="d-flex">
        <Btn btnClass="btn-link">Buttons</Btn>
        <Btn btnClass="btn-link" icon-prev-text="IconPlus">Button</Btn>
        <Btn btnClass="btn-link" icon-next-text="IconNext">Button</Btn>
        <Btn
          btnClass="btn-link"
          icon-prev-text="IconPlus"
          icon-next-text="IconNext"
        >
          Button
        </Btn>
      </div>
      <div class="d-flex bg-primary">
        <Btn btnClass="btn-link-white">Buttons</Btn>
        <Btn btnClass="btn-link-white" icon-prev-text="IconPlus">Button</Btn>
        <Btn btnClass="btn-link-white" icon-next-text="IconNext">Button</Btn>
        <Btn
          btnClass="btn-link-white"
          icon-prev-text="IconPlus"
          icon-next-text="IconNext"
        >
          Button
        </Btn>
      </div>
    </div>
    <h2 class="block-title">Tooltip</h2>
    <div class="block">
      <div class="d-flex">
        <Btn btnClass="btn-outline-primary btn-tooltip btn-tooltip-top"
          >tooltip</Btn
        >
        <Btn btnClass="btn-outline-primary btn-tooltip btn-tooltip-left"
          >tooltip</Btn
        >
        <Btn btnClass="btn-outline-primary btn-tooltip btn-tooltip-bottom"
          >tooltip</Btn
        >
        <Btn btnClass="btn-outline-primary btn-tooltip btn-tooltip-right"
          >tooltip</Btn
        >
      </div>
      <div class="d-flex">
        <Btn btnClass="btn-primary btn-tooltip btn-tooltip-top">tooltip</Btn>
        <Btn btnClass="btn-primary btn-tooltip btn-tooltip-left">tooltip</Btn>
        <Btn btnClass="btn-primary btn-tooltip btn-tooltip-bottom">tooltip</Btn>
        <Btn btnClass="btn-primary btn-tooltip btn-tooltip-right">tooltip</Btn>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      horizontalNav: [
        { text: "Active", icon: "IconHome", active: true },
        { text: "Inactive", icon: "IconInactive", active: false },
        { text: "Inactive", icon: "IconUser", active: false },
      ],
      breadcrumb: [{ text: "Home" }],
      breadcrumb1: [{ text: "Home" }, { text: "Products" }],
      breadcrumb2: [{ text: "Home" }, { text: "Products" }, { text: "Laptop" }],
      breadcrumb3: [
        { text: "Home" },
        { text: "Products" },
        { text: "Laptop" },
        { text: "Features" },
      ],
      btnList: [
        {
          text: "Button",
          status: true,
        },
        {
          text: "Button",
          status: false,
        },
      ],
      btnList1: [
        {
          text: "Button",
          status: true,
        },
        {
          text: "Button",
          status: false,
        },
        {
          text: "Button",
          status: false,
        },
      ],
      btnList2: [
        {
          text: "Button",
          status: true,
        },
        {
          text: "Button",
          status: false,
        },
        {
          text: "Button",
          status: false,
        },
        {
          text: "Button",
          status: false,
        },
      ],
      btnList3: [
        {
          text: "Button",
          status: true,
        },
        {
          text: "Button",
          status: false,
        },
        {
          text: "Button",
          status: false,
        },
        {
          text: "Button",
          status: false,
        },
        {
          text: "Button",
          status: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss">
.block {
  width: fit-content;
  min-width: 500px;
  padding: 10px 0;
  box-sizing: border-box;
  border: 1px solid $primary;
  border-radius: 6px;
  margin: 20px;
  &-title {
    font-weight: 600;
    font-size: 28px;
    line-height: 44px;
    color: $primary;
    margin: 24px 20px;
  }
  .d-flex {
    display: flex;
  }
  .align-items-center {
    align-items: center;
  }
  .btn {
    margin: 12px 15px;
  }
}
</style>
