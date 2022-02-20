<template>
  <div class="admin">
    <PageTitle icon="fa fa-cogs" main="Administração do Sistema"
      sub="Cadastros & Cia" />
      <div class="admin-pages-tabs">
        <b-card no-body>
          <b-tabs card >
            <b-tab title="Artigos" active>
              <ArticleAdmin />
            </b-tab>
            <b-tab title="Categorias">
              <CategoriesAdmin />
            </b-tab>
            <b-tab title="Usuários">
              <UsersAdmin />
            </b-tab>
          </b-tabs>
        </b-card>
      </div>
  </div>
</template>

<script>
import PageTitle from "../template/PageTitle.vue";
import ArticleAdmin from "../admin/ArticleAdmin.vue";
import CategoriesAdmin from "../admin/CategoryAdmin.vue";
import UsersAdmin from "../admin/UserAdmin.vue";
export default {
  name: "AdiminPages",
  components: { PageTitle, ArticleAdmin, CategoriesAdmin, UsersAdmin },
};
</script>

<style>
</style>
