# Railsguide Tutorial 

## Introduction

A simple web blog app made following rails guide tutorial.

## Code Samples

  def destroy
    @article = Article.find(params[:id])
    @article.destroy

    redirect_to articles_path
  end

## Installation

Copy the files and migrate the DB.
