<script lang="ts" setup>
import VerticalNavLink from '@layouts/components/VerticalNavLink.vue'
import VerticalNavSectionTitle from '@/@layouts/components/VerticalNavSectionTitle.vue'
</script>

<template>
  <VerticalNavLink
    :item="{
      title: 'Trang chủ',
      icon: 'ri-home-3-line',
      to: '/dashboard',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Quản lý tin đăng',
      icon: 'ri-article-line',
      to: '/profile-post',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Thông tin cá nhân',
      icon: 'ri-user-line',
      to: '/account-settings',
    }"
  />
  <VerticalNavSectionTitle
    :item="{
      heading: 'Dịch vụ',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Nạp tiền',
      icon: 'ri-money-dollar-circle-line',
      to: '/service-recharge',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Lịch sử nạp tiền',
      icon: 'ri-calendar-line',
      to: '/service-history-recharge',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Lịch sử thanh toán',
      icon: 'ri-calendar-schedule-line',
      to: '/service-history-payment',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Bảng giá dịch vụ',
      icon: 'ri-price-tag-3-line',
      to: '/service-price',
    }"
  />
  <VerticalNavSectionTitle
    :item="{
      heading: 'Khác',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Liên hệ',
      icon: 'ri-contacts-book-3-line',
      to: '/contact-us',
    }"
  />
</template>
