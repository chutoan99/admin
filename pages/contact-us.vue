<script lang="ts" setup>
const query = gql`
  query {
  area {
    err
    msg
    response {
      code
      createdAt
      id
      order
      updatedAt
      value
    }
  }
}`

const { data } = useAsyncQuery(query)

console.log(data.value as 'cscscs')
</script>

<template>
  <div>
    <VRow>
      <VCol cols="12">
        <VCard title="Liên hệ" />
      </VCol>
    </VRow>
  </div>
</template>
